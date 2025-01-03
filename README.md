# T-Rex Oyunu için Derin Öğrenme Modeli

## Amaç / Purpose
T-Rex oyununun grafiklerinden ilham alınarak bir sinir ağı modeli geliştirildi. Bu proje, T-Rex karakterini farklı hareket durumlarıyla tanıyabilen bir model üzerine odaklanmıştır.

Inspired by the graphics of the T-Rex game, a neural network model was developed. This project focuses on a model that can recognize the T-Rex character in different motion states.

---

## Kullanılan Teknikler / Techniques Used

- **Veri İşleme** / **Data Processing**
  - Resim boyutlandırma ve gri tonlama / Image resizing and grayscale conversion
  - Normalizasyon / Normalization
  - Etiketlerin One-Hot Encoding ile nümarikleştirilmesi / One-hot encoding of labels

- **Model Yapısı** / **Model Architecture**
  - **Evrişimsel Katmanlar (Conv2D)** / **Convolutional Layers (Conv2D)**
  - **Havuzlama Katmanı (MaxPooling2D)** / **Pooling Layer (MaxPooling2D)**
  - **Tam Bağlı (Dense) Katmanlar** / **Fully Connected (Dense) Layers**
  - **Dropout** ile ağırlıkların seyreltilmesi / Dropout for regularization

- **Model Eğitimi** / **Model Training**
  - Kategorik çapraz entropi kaybı fonksiyonu / Categorical cross-entropy loss function
  - Adam optimizerı ile optimize etme / Optimization with Adam optimizer

---

## Sonuçlar / Results

- **Eğitim Doğruluğu / Training Accuracy:** %{{score_train}}  
- **Test Doğruluğu / Test Accuracy:** %{{score_test}}

Model, T-Rex oyununun farklı hareketlerini başarıyla tanıyabilmektedir.

The model successfully recognizes different movements of the T-Rex character.

---

## Kurulum ve Kullanım / Installation and Usage

1. **Bağımlılıkları Yükleyin** / **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Proje Dizinine Gidin** / **Navigate to the Project Directory:**
   ```bash
   cd Trex_with_CNN
   ```



