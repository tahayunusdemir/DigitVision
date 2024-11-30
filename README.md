
# DigitVision

## Proje Açıklaması  
Bu proje, Kaggle'ın ünlü **Digit Recognizer** yarışmasında verilen MNIST veri seti üzerinde el yazısı rakam sınıflandırma işlemi yapmayı amaçlamaktadır. Proje boyunca PyTorch kütüphanesi kullanılmış ve eğitim, değerlendirme ile tahmin süreçleri detaylı bir şekilde gerçekleştirilmiştir.

## Kullanılan Teknolojiler  
- **Dil:** Python  
- **Kütüphaneler:** 
  - PyTorch: Derin öğrenme modeli oluşturma ve eğitme  
  - NumPy & Pandas: Veri işleme  
  - Matplotlib & Seaborn: Veri görselleştirme  
  - Scikit-learn: Sınıflandırma raporu ve karışıklık matrisi  

## Özellikler  
- MNIST veri seti kullanılarak eğitim ve test işlemleri  
- Veri augmentasyonu ile modelin genel performansını artırma  
- Gelişmiş bir CNN (Convolutional Neural Network) ile yüksek doğruluk elde etme  
- Eğitim kayıplarını görselleştirme  
- Karışıklık matrisi ve sınıflandırma raporu oluşturma  
- Test veri setine yönelik tahminleri **sonuç.csv** formatında kaydetme  

## Kullanım  

### Gereksinimler  
Projenin çalıştırılabilmesi için aşağıdaki yazılımlar ve kütüphaneler gereklidir:  
- Python 3.8+  
- PyTorch  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  

### Proje Çıktıları  
Proje sırasında üretilen çıktı görsellerini `çıktılar` klasöründe bulabilirsiniz. Test sonuçları ise `sonuç.csv` dosyasında yer almaktadır. 

## Proje Yapısı  
```plaintext
DigitVision/
├── main.ipynb                    # Ana proje dosyası
├── rapor.docx                    # Rapor dosyası
├── train.csv                     # Eğitim veri seti
├── test.csv                      # Test veri seti
├── sonuç.csv                     # Tahmin sonuçları
├── çıktılar/                     # Çıktı görselleri
│   ├── Eğitim kayıpları.png      # Eğitim kayıpları grafiği
│   ├── Karışıklık matrisi.png    # Karışıklık matrisi
├── README.md                     # Proje açıklama dosyası
└── requirements.txt              # Gerekli kütüphaneler

```
