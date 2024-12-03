# Convolutional Neural Network for Image Classification

![Marine Mammal Spectrogram](images/header_image.png)

Welcome to the **Convolutional Neural Network (CNN)** project! This repository is dedicated to building a deep-learning model for sound detection by classifying spectrogram images generated from audio signals. The project utilizes techniques such as **Residual Connections**, **Batch Normalization**, and **Global Average Pooling** to handle the dataset effectively.

The primary goal of this project is to detect and classify audio signals (e.g., marine mammal sounds) by converting them into spectrogram images, which are visual representations of the sound's frequency content over time. The CNN model is trained to analyze these spectrograms and identify distinct audio patterns associated with different classes of sounds.

---

## Key Highlights

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

## Project Structure

```plaintext
.
├── main.ipynb         # Jupyter Notebook containing the model code and training steps

---

## Requirements

This project requires Python and the following Python libraries:

- TensorFlow or Keras
- NumPy
- Matplotlib

## Contributing
Contributions are welcome! Feel free to fork the repository and submit a pull request. For major changes, please open an issue first to discuss your ideas.

