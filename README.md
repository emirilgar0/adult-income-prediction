Adult Census Income Prediction
Bu proje, Adult Census Income veri seti kullanılarak bireylerin yıllık gelirlerinin 50.000 dolardan fazla olup olmadığını tahmin eden bir ikili sınıflandırma (binary classification) çalışmasıdır.

Veri Ön İşleme ve Özellik Mühendisliği
Kategorik veriler One-Hot Encoding ile dönüştürülmüş, sayısal veriler ise StandardScaler ile ölçeklendirilmiştir.

Veri setine capital_diff ve age_bucket gibi yeni özellikler eklenmiştir.

Sınıf dengesizliği problemini çözmek için SMOTE (Synthetic Minority Over-sampling Technique) yöntemi kullanılmıştır.

Modeller ve Performans
Proje kapsamında Lojistik Regresyon, Random Forest, SVM ve Yapay Sinir Ağları (MLP) dahil olmak üzere toplam 10 farklı makine öğrenmesi algoritması test edilmiştir.

Yapılan değerlendirmeler sonucunda en yüksek performansı Gradient Boosting Classifier göstermiştir. En başarılı modelin metrikleri şöyledir:

Accuracy: 0.861

Precision: 0.773

Recall: 0.598

F1-Score: 0.675
