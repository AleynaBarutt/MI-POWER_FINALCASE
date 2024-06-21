## Water Quality Analysis

![1](https://github.com/AleynaBarutt/MI-POWER_FINALCASE/assets/63070084/6a449d4a-e3d7-43a3-9c66-9fa77d344afe)


## Motivasyon ve Arka Plan
Su kalitesinin içilebilirliğe etkisinin analizi, gerçek dünyada önemli bir öneme sahiptir. Su, insan sağlığı için temel bir kaynaktır. Ancak suyun içilebilirliği, güvenliği ve içme amaçlarına uygunluğuna bağlıdır.

Bu analiz aracılığıyla, su kalitesini etkileyen faktörleri anlamak ve değerlendirmek mümkün hale gelir. Örneğin, pH değeri, sertlik seviyesi ve kimyasal bileşim gibi su özelliklerinin içilebilirliğe etkileri incelenebilir. Bu bilgi, su kaynakları yönetimi ve su temin süreçlerinin iyileştirilmesi için kritik veriler sağlar.

Ayrıca, su kaynaklarının kirlilik seviyelerinin belirlenmesi ve içilebilirlik standartlarına uyumunun değerlendirilmesi, sağlık kurumları, su temininden sorumlu organizasyonlar ve karar vericiler için önemlidir. Su kaynaklarının içilebilirlik durumu hakkında bilgi sahibi olmak, sağlık risklerini en aza indirmek ve halk sağlığını korumak için önlemler alınmasına olanak tanır.

Sonuç olarak, su kalitesinin içilebilirliğe etkisinin değerlendirilmesi, su kaynaklarının korunması, su temininin güvenliği ve sağlık standartlarının sürdürülmesi konusunda değerli bilgiler sunar. Bu analiz, su kaynaklarının sürdürülebilir kullanımını destekleyerek insan sağlığı ve çevre üzerinde olumlu etkiler yaratır.

## Veri Kümesi Bilgileri

Bu veri kümesi, su kalitesi ve içilebilirlik durumu ile ilgili özellikleri içeren bir su kalitesi analiz veri kümesidir. Veri kümesi ile ilgili bazı detaylar aşağıda verilmiştir:

Veri kümesi toplamda 3.276 gözlem ve 10 değişken içermektedir.
Değişkenler arasında pH değeri, sertlik seviyesi, klorür, sülfat ve sıcaklık gibi suyun fiziksel ve kimyasal özellikleri bulunmaktadır.
İçilebilirlik durumu, suyun içilebilirliğini temsil eder. İçilebilirlik değeri 1 olan su içilebilir, 0 olan su ise içilemez olarak kabul edilir. Bu nedenle, iki sınıf vardır (İçilebilir: 1 ve İçilemez: 0).
Veri kümesinde bazı değişkenlerde eksik değerler bulunmaktadır. Bu eksik değerler analiz yapılırken dikkate alınmalıdır.
Su kalitesinin içilebilirlik durumuna etkilerini ve ilişkilerini incelemek için istatistiksel analizler, görselleştirmeler ve makine öğrenimi algoritmaları uygulanabilir.
Bu veri kümesi, su kaynaklarının içilebilirlik durumunu anlamak, su kalitesini iyileştirmek ve içme suyu güvenliği için önlemler almak amacıyla kullanılabilir. Bu veri kümesi üzerinde yapılan analizler, su kaynaklarının yönetimi, su temin süreçlerinin optimizasyonu ve güvenli içme suyu sağlanmasında önemli bir rol oynayabilir.

Veri kümesinde pH sütununda 491 eksik değer, sülfat sütununda 781 ve trihalometanlar sütununda 162 eksik değer bulunmaktadır. Toplamda 1.434 eksik değer mevcuttur.

**Data Set:** [Water Potability Dataset on Kaggle](https://www.kaggle.com/datasets/adityakadiwal/water-potability)


## Kullanılan Algoritmalar
- Logistic Regression
- Support Vector Machines (SVM Sınıflandırma)
- Random Forest
- AdaBoost
- XGBoost
- CatBoost
- LightGBM

## Kullanılan Kütüphaneler
Kullanılan kütüphaneler arasında Flask, Pandas, NumPy, Matplotlib ve Plotly bulunmaktadır. Kod, bir Flask uygulaması oluşturur ve veri analizi görevlerini yerine getirir.

## Veri Analizi Adımları
Veri analizi adımları şunlardır:

- Veri yükleme
- Özet istatistiklerin oluşturulması
- Eksik veri analizi
- Aykırı değer tespiti
- Veri görselleştirme

## Algoritma Performansı

- Logistic Regression: %63.1 doğruluk
- SVC: %63.3 doğruluk
- Random Forest: %76.3 doğruluk
- AdaBoost: %75.9 doğruluk
- XGBoost: %76.9 doğruluk
- CatBoost: %77.7 doğruluk
- LightGBM: %77.8 doğruluk

## Eğitim ve Test: (overfit)

- LightGBM Doğruluk: %77.8
- LightGBM Eğitim Doğruluğu: %99.4

- Random Forest Doğruluk: %76.3
- Random Forest Eğitim Doğruluğu: %100

- CatBoost Doğruluk: %77.7
- CatBoost Eğitim Doğruluğu: %94.8

## Parametre Optimizasyonu 

- XGBoost: En İyi Skor: %79.4
- LightGBM: En İyi Skor: %79.5
- CatBoost: En İyi Skor: %80.1
- Random Forest: %80.4

## Algoritma Performansı (Değişikliklerden sonra (aykırı değerler, eksik veriler, kategorilendirme))

- Logistic Regression: %57.7
- SVC: %57.7
- Random Forest: %69.5
- XGBoost: %66.2
- LightGBM: %69.1
- CatBoost: %72.6
- AdaBoost: %58.0

## Tahmin
Web uygulaması kullanıcılara tahmin yapma olanağı sağlar. Tahmin sonuçları kullanıcıya sunulur. Veri kümesinden alınan örnek girdilerle test edildiğinde, tahmin sonuçları doğru çıkmaktadır. Bu, modelin veri kümesinden örnek girdilerle doğru sonuçlar üretebildiğini gösterir.
