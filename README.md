# Aygaz-Yapay-Zekaya-Giri-Bootcamp-
## Projenin Amacı
Bu proje, Fashion MNIST veri setini kullanarak çeşitli makine öğrenmesi ve derin öğrenme modelleriyle giysi sınıflandırması yapmayı amaçlamaktadır. Amaç, farklı algoritmaların performansını karşılaştırarak en iyi sınıflandırma sonuçlarını elde etmektir.

## Kullanılan Veri Seti
- **Fashion MNIST:** 10 farklı giysi kategorisine ait 70.000 gri tonlamalı görüntü. Her görüntü 28x28 piksel boyutundadır. Veri seti, 60.000 eğitim ve 10.000 test örneğine bölünmüştür.

İşte verilerin nasıl göründüğüne dair bir örnek:
![fashion-mnist-sprite](https://github.com/irem0604/Aygaz-Yapay-Zekaya-Giris-Bootcamp-/assets/173558753/4edc97c9-3d4c-4fa3-aa2d-76f4b0fcf524)

## Kullanılan Modeller
Bu projede aşağıdaki makine öğrenmesi ve derin öğrenme modelleri kullanılmıştır:
- **K-Nearest Neighbors (KNN)**
- **Support Vector Machines (SVM)**
- **Decision Tree**
- **Random Forest**
- **Logistic Regression**
- **Yapay Sinir Ağları (ANN)**

## Sonuçlar
Modellerin karşılaştırmalı performans sonuçları aşağıdaki gibidir:

| Model                   | Accuracy | Precision | Recall   | F1-Score |
|-------------------------|----------|-----------|----------|----------|
| **KNN**                 | 0.8554   | 0.8578    | 0.8554   | 0.8546   |
| **Random Forest**       | 0.8771   | 0.8760    | 0.8771   | 0.8756   |
| **Decision Tree**       | 0.7905   | 0.7919    | 0.7905   | 0.7911   |
| **SVC**                 | 0.8828   | 0.8823    | 0.8828   | 0.8823   |
| **Logistic Regression** | 0.8412   | 0.8397    | 0.8412   | 0.8399   |
| **ANN**                 | 0.8927   | 0.9085    | 0.8675   | 0.8926   |


