# 👕 Fashion-MNIST: Sınıf Bazlı Performans İyileştirme ve Görsel Test Planı

## 📌 Giriş
Bu proje, Fashion-MNIST veri seti üzerinde sınıf bazlı ayrım başarısını artırmak amacıyla yürütülmüştür. Özellikle Shirt sınıfı gibi görsel benzerlik kaynaklı hata üreten sınıflarda targeted augmentasyon, hiperparametre optimizasyonu ve açıklanabilirlik teknikleri uygulanmıştır. Notebook içerisinde tüm teknik süreç markdown hücreleriyle belgelenmiş; preprocessing, model eğitimi, metrik analizi ve görsel test altyapısı adım adım sunulmuştur.

## 🎯 Proje Amacı
Modelin sınıf bazlı davranışını analiz ederek, düşük başarı gösteren sınıflarda targeted stratejilerle performans iyileştirmek; metrik takibi ve görsel testlerle modelin genelleme kapasitesini değerlendirmek.

## 📊 Metrikler
• 	Doğruluk: %92
• 	Validation Loss: 0.2378
• 	En yüksek F1 skorunu üreten yapı: Early Stop + Opt
• 	Zayıf sınıflar: Shirt, T-shirt/top, Pullover
• 	Güçlü sınıflar: Bag, Sneaker, Ankle boot
• 	Analizler: Confusion matrix, recall, precision, F1-score

## 🧪 Teknik Süreç
• 	Veri ön işleme: normalize, reshape, grayscale
• 	Model mimarisi: CNN + Dropout + Dense
• 	Eğitim stratejileri: Early stopping, learning rate tuning
• 	Görsel test planı: Kaggle ortamında açık kaynak görsellerle gerçeklik testi
• 	Açıklanabilirlik: Grad-CAM ile dikkat bölgelerinin görselleştirilmesi


## 🚀 Sonuç ve Gelecek Çalışmalar
Model, sınıf bazlı stratejilerle yönlendirilmiş ve metriklerle doğrulanmıştır. Gerçek dünya görselleriyle test süreci bir sonraki fazda tamamlanacaktır. Görsel benzerlik kaynaklı hatalar üzerine detaylı analiz planlanmakta; proje, üretim ortamına entegrasyon ve gerçek zamanlı veri toplama gibi adımlarla genişletilecektir.

🔗 Linkler
• 	[Kaggle Notebook](https://www.kaggle.com/code/asli77/fashiontune)
• 	[Kaggle Veri Seti](https://www.kaggle.com/datasets/zalando-research/fashionmnist)
