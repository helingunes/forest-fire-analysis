# forest-fire-analysis
Forest fire prediction using Decision Tree Regression
 Orman Yangını Analizi

Bu projede, makine öğrenmesi yöntemlerinden **Karar Ağacı Regresyonu (Decision Tree Regressor)** kullanılarak orman alanı ve yangın ile ilişkili faktörler analiz edilmiştir.
 Projenin Amacı

Bu çalışmanın amacı, çevresel ve ekonomik değişkenleri kullanarak orman alanı ve potansiyel yangın riskini tahmin etmektir.

Kullanılan Veri Seti

Projede aşağıdaki değişkenler kullanılmıştır:

- Tarım alanı (agri_km2)
- Toplam arazi (land_km2)
- Karbon salınımı zararı (% GNI)
- Orman alanı (forest_km2) → hedef değişken

 Kullanılan Yöntemler

- Karar Ağacı Regresyonu
- Eğitim / Test veri bölme
- Model optimizasyonu (max_depth, criterion vb.)
- Performans metrikleri:
  - MSE (Mean Squared Error)
  - RMSE
  - MAE
  - R² Score
  - Explained Variance

Model Değerlendirme

Model performansı çeşitli metrikler ile değerlendirilmiştir. Ayrıca karar ağacı yapısı görselleştirilerek modelin karar mekanizması analiz edilmiştir.

 Ek Analizler

- Ağaç yapısındaki düğümlerin impurity değerleri incelenmiştir
- Bilgi kazancı hesaplanmıştır
- Özelliklerin model üzerindeki etkisi analiz edilmiştir

 Kullanılan Teknolojiler

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

sonuç

Bu çalışma, makine öğrenmesi tekniklerinin çevresel veri analizi ve orman yangını tahmini gibi problemlerde etkili bir şekilde kullanılabileceğini göstermektedir.
