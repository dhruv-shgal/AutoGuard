# 💤 Drowsiness Detection System

The **Drowsiness Detection System** is an AI-powered safety solution designed to monitor and detect signs of driver fatigue or drowsiness using computer vision and deep learning techniques. Built with OpenCV, TensorFlow, and Keras, this project classifies facial features into alert, drowsy, or sleepy states based on real-time video analysis.

---

## 📌 Key Features

- 👁️ Real-time eye and facial expression tracking
- 🤖 Deep learning model (CNN) for high-accuracy drowsiness classification
- 🎥 Video stream integration using OpenCV
- 🔔 Visual alert system for detected drowsiness
- 💻 Cloud-based training via Google Colab

---

## 🛠️ Technologies Used

- **Language:** Python
- **Libraries:** OpenCV, TensorFlow, Keras, NumPy, Matplotlib, Seaborn
- **Model:** Custom Convolutional Neural Network (CNN)
- **Environment:** Google Colab

---

## 🧠 Dataset

- **Classes:** Sleepy (1200 images), Drowsy (1000 images), Awake/Active (1500 images)
- **Source:** Public human facial datasets
- **Augmentation:** Flipping, rotation, brightness, cropping

---

## 🧱 Model Architecture

- **Input Layer:** 224x224 grayscale images
- **Conv Layers:** Two convolutional blocks with ReLU and max-pooling
- **Normalization:** BatchNormalization for training stability
- **Dense Layers:** Fully connected layers with Dropout
- **Output Layer:** Softmax activation with 3 output classes

---

## 🚀 How to Run

1. **Clone the Repository**
   ```bash
   git clone https://github.com/your-username/drowsiness-detection.git
   cd drowsiness-detection
