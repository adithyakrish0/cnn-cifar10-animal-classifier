# 🐾 CIFAR-10 Animal Classifier using CNN

This project is a Convolutional Neural Network (CNN)-based image classification model trained on a subset of the CIFAR-10 dataset. The model focuses on classifying **animal categories** — specifically: **bird, cat, deer, dog, and horse**.

## 📂 Dataset

- Source: [CIFAR-10](https://www.cs.toronto.edu/~kriz/cifar.html)
- Total Classes in CIFAR-10: 10
- Filtered Classes Used:
  - Bird
  - Cat
  - Deer
  - Dog
  - Horse

## 🧠 Model Architecture

The CNN consists of:

- 3 Convolutional layers with increasing filters (32, 64, 128)
- MaxPooling layers for spatial downsampling
- Dense layer for learning complex features
- Softmax output layer for multi-class classification

Trained with:
- `Adam` optimizer
- `sparse_categorical_crossentropy` loss
- `ImageDataGenerator` for data augmentation

## 📈 Performance

- Trained over 15 epochs with real-time data augmentation.
- Achieved ~71% accuracy on the filtered test set.

## 🔍 Demo: Predict Animal from Custom Image

You can upload your own image of an animal (bird, cat, deer, dog, or horse) and the model will predict its species with confidence score.

Example output:
![image](https://github.com/user-attachments/assets/d1bdf9a4-97de-4ca0-b1cd-45d0b77babcc)

![Untitled](https://github.com/user-attachments/assets/acd663dc-17ca-4fbb-aa6b-efbe8071c410)


## 🛠️ Technologies Used

- Python 🐍
- TensorFlow / Keras
- NumPy
- PIL
- Matplotlib
- Google Colab

## 🚀 How to Run

1. Open the `.ipynb` file in [Google Colab](https://colab.research.google.com/)
2. Run all cells
3. Upload an image when prompted to see the prediction

---

## 📸 Sample Predictions

| Image | Predicted |
|-------|-----------|
| ![dog](example_images/dog.jpg) | Dog |
| ![bird](example_images/bird.jpg) | Bird |

> You can replace with your own images to test.

---

## 📜 License

This project is licensed under the MIT License.

---


