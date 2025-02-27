Smoking Detection

Bu proje, görüntü işleme ve makine öğrenmesi teknikleri kullanarak sigara içme tespiti yapan bir sistem geliştirmeyi amaçlamaktadır.

📌 Proje Açıklaması

Smoking Detection, video ve görüntü verileri üzerinden sigara içen kişileri tespit eden bir yapay zeka modelidir. Bu proje, özellikle kapalı alanlarda sigara kullanımını kontrol etmek, kamu sağlığını korumak ve ilgili düzenlemelere uyumu artırmak için geliştirilmiştir.

🛠 Kullanılan Teknolojiler

Python 3.13

TensorFlow/Keras - Derin öğrenme modeli oluşturma

OpenCV - Görüntü işleme

YOLOv8 - Nesne tespiti

Scikit-learn - Veri işleme ve model değerlendirme

📥 Kurulum

Proje dosyalarını klonladıktan sonra aşağıdaki adımları takip ederek ortamınızı hazırlayabilirsiniz:

1️⃣ Depoyu Klonlayın
```
 git clone https://github.com/kullaniciadi/Smoking_Detection.git
 cd Smoking_Detection
```
2️⃣ Gerekli Kütüphaneleri Yükleyin
```
pip install -r requirements.txt
```
3️⃣ Modeli Eğitin veya Hazır Modeli Kullanın

Eğer kendi modelinizi eğitmek istiyorsanız:
```
python train.py --epochs 50
```
Hazır modeli kullanmak için:
```
python detect.py --model trained_model.h5
```
🚀 Kullanım

Gerçek Zamanlı Tespit
```
python detect.py --source 0
```
Video Üzerinden Tespit
```
python detect.py --source video.mp4
```
📊 Model Performansı

Doğruluk 94.5%

Kayıp 91.2%


