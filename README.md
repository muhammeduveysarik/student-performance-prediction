# Öğrenci Akademik Başarı Tahmini

## Proje Hakkında
Bu proje, öğrencilerin akademik ve demografik özelliklerini kullanarak başarı durumlarını makine öğrenmesi algoritmalarıyla tahmin etmeyi amaçlamaktadır.

## Veri Seti
- Kaynak: UCI Student Performance Dataset
- Öğrenci sayısı: 395
- Tahmin değişkeni sayısı: 30
- Hedef: Başarılı (G3 ≥ 10) veya başarısız (G3 < 10)

## Kullanılan Teknolojiler
- Python
- Pandas
- Matplotlib ve Seaborn
- Scikit-learn
- Google Colab

## Kullanılan Modeller
1. Logistic Regression
2. Random Forest

## Model Sonuçları

| Model | Accuracy | Precision | Recall | F1 |
|---|---|---|---|---|
| Logistic Regression | 0.6582 | 0.7167 | 0.8113 | 0.7611 |
| Random Forest | 0.6329 | 0.6765 | 0.8679 | 0.7603 |

## Sonuç
Logistic Regression modeli, test kümesinde accuracy ve F1 skorlarında küçük bir farkla daha yüksek performans göstermiştir. Random Forest modeli ise başarılı öğrencileri belirlemede daha yüksek recall elde etmiştir.

Modellerin daha güvenilir şekilde karşılaştırılması için çapraz doğrulama ve hiperparametre optimizasyonu gelecekte uygulanabilir.

## Çalıştırma
`ogrenci_basari_tahmini.ipynb` dosyasını Google Colab üzerinde açın ve hücreleri sırasıyla çalıştırın.

## Veri Kaynağı
https://archive.ics.uci.edu/dataset/320/student+performance
