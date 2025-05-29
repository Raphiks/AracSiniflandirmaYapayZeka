Car Evaluation Dataset - Araç Değerlendirme Projesi 🚗
Bu proje, UCI Machine Learning Repository'den alınan Car Evaluation Dataset kullanılarak araçların bazı özelliklerine göre kabul edilebilirlik durumlarını (acceptability) tahmin eden bir makine öğrenmesi uygulamasıdır. Projede veriler temizlenmiş, görselleştirilmiş ve farklı makine öğrenimi algoritmaları ile sınıflandırma modelleri oluşturulmuştur.

📊 Kullanılan Özellikler:
AlışFiyatı (vhigh, high, med, low)

BakımMaliyeti (vhigh, high, med, low)

KapıSayısı (2, 3, 4, 5+)

YolcuSayısı (2, 4, more)

BagajBoyutu (small, med, big)

Konfor (low, med, high)

Karar (hedef değişken): unacc (kabul edilemez), acc (kabul edilebilir)

⚙️ Uygulanan Modeller:
Random Forest

Decision Tree

k-Nearest Neighbors (k-NN)

Support Vector Machine (SVM)

Logistic Regression

📈 Model Performansları:
En iyi doğruluk oranı Logistic Regression modeliyle elde edilmiştir: %89.03

Diğer modeller de %72 ile %86 arasında doğruluk oranlarına sahiptir.

ROC eğrisi ve Confusion Matrix kullanılarak modellerin başarısı detaylıca analiz edilmiştir.

📦 Kullanılan Kütüphaneler:
pandas, matplotlib, seaborn

sklearn (scikit-learn)

🎯 Hedef:
Bu projenin amacı, farklı makine öğrenimi algoritmalarını kullanarak araç değerlendirme sınıflandırmasını karşılaştırmalı olarak analiz etmektir.
