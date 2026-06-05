# Airbnb Demand Prediction: Istanbul vs Paris

Bu projede İstanbul ve Paris Airbnb listing verileri kullanılarak talep tahmini yapılmıştır. Talep göstergesi olarak `reviews_per_month` değişkeni kullanılmıştır.

## Dataset

Veriler Inside Airbnb Get the Data sayfasından indirilmiştir:
https://insideairbnb.com/get-the-data/

Kullanılan dosyalar:
- Istanbul listings dataset
- Paris listings dataset

## Kullanılan Yöntemler

Projede aşağıdaki modeller karşılaştırılmıştır:

- Naive Baseline
- Linear Regression
- Ridge Regression
- Random Forest Regressor

## Değerlendirme Metrikleri

Model performansı şu metriklerle değerlendirilmiştir:

- RMSE
- MAE
- R²

## Ana Sonuçlar

Random Forest modeli iki şehirde de en iyi sonucu vermiştir.

| City | RMSE | MAE | R² |
|---|---:|---:|---:|
| Istanbul | 0.3113 | 0.2087 | 0.6196 |
| Paris | 0.3137 | 0.2153 | 0.5923 |

## Not

Bu çalışma nedensel analiz değildir. Feature importance sonuçları, değişkenlerin tahmin sürecindeki önemini gösterir; talebi kesin olarak artırdığını veya azalttığını göstermez.
