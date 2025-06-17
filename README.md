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

![image](https://github.com/user-attachments/assets/1f3f179d-b5ed-4096-875a-4c6872bff67f)

![Untitled](https://github.com/user-attachments/assets/f2ca3348-f2f8-45ec-8a71-eccf7ccecabb)

![image](https://github.com/user-attachments/assets/6efa3e9b-56b1-4c5c-9dd6-f2b4213a08ed)

![Untitled](https://github.com/user-attachments/assets/eeee2a7d-ca53-41bb-b04f-e5012663c722)

![image](https://github.com/user-attachments/assets/07fd4e9f-9316-45f2-97c0-44fc77e658a3)

![image](https://github.com/user-attachments/assets/e2c66a1b-51f9-46c2-8d18-4ef7b1aaaeb5)
![Untitled](https://github.com/user-attachments/assets/553740ae-c86d-48d4-a3fd-28a55e2616c8)



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


