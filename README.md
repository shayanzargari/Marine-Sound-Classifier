# 🐬 CNN for Marine Mammal Sound Classification

Welcome to the **Convolutional Neural Network (CNN)** project! This repository is dedicated to building a deep-learning model for sound detection by classifying spectrogram images generated from audio signals. The project utilizes techniques such as **Residual Connections**, **Batch Normalization**, and **Global Average Pooling** to handle the dataset effectively.

The primary goal of this project is to detect and classify audio signals (e.g., marine mammal sounds) by converting them into spectrogram images, which are visual representations of the sound's frequency content over time. The CNN model is trained to analyze these spectrograms and identify distinct audio patterns associated with different classes of sounds.

---
## 📂 Dataset

This project uses the **Best of Watkins Marine Mammal Sound Database**, available on Kaggle. The dataset contains high-quality recordings of marine mammal sounds.

You can access the dataset here:  
[Best of Watkins Marine Mammal Sound Database on Kaggle](https://www.kaggle.com/datasets/shreyj1729/best-of-watkins-marine-mammal-sound-database?utm_source=chatgpt.com)

---

## 🌟 Key Highlights

- **CNN Architecture**:
  - Residual connections for improved gradient flow.
  - Batch normalization for faster convergence.
  - Global average pooling to reduce parameter count.
- **Regularization**:
  - Dropout layers to prevent overfitting.
- **Flexibility**:
  - Adjustable for different input sizes and number of classes.
- **Scalability**:
  - Easy to extend or modify for other image datasets or tasks.

---

## Requirements

This project requires Python and the following Python libraries:

- TensorFlow or Keras
- NumPy
- Matplotlib

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss your ideas.

