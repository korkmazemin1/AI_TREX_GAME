# AI Takes the Reins: A Deep Learning Model Plays the T-Rex Game

## Purpose
Inspired by the graphics of the T-Rex game, a neural network model was developed. This project focuses on a model that can recognize the T-Rex character in different motion states.

---

## Techniques Used

- **Data Processing**
  - Image resizing and grayscale conversion
  - Normalization
  - One-hot encoding of labels

- **Model Architecture**
  - **Convolutional Layers (Conv2D)**
  - **Pooling Layer (MaxPooling2D)**
  - **Fully Connected (Dense) Layers**
  - Dropout for regularization

- **Model Training**
  - Categorical cross-entropy loss function
  - Optimization with Adam optimizer

---

## Results

- **Training Accuracy:** %{{score_train}}  
- **Test Accuracy:** %{{score_test}}

The model successfully recognizes the different movements of the T-Rex character.

---

## Installation and Usage

1.  **Navigate to the Project Directory:**
    ```bash
    cd Trex_with_CNN
    ```

2. **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
