# SimpleAgeEstimator
Age Prediction from Faical Images using CNN


# 🧠 Age Prediction from Images using CNN

This project uses a **Convolutional Neural Network (CNN)** to perform **age regression** from facial images. It predicts a person’s age based on an input image using deep learning techniques implemented in TensorFlow/Keras.

> 📌 *This was one of my first projects using CNNs, developed during my undergraduate (Bachelor's) studies a few years ago. While simple, it helped me understand core deep learning concepts and model building.*

---

## 📁 Project Structure
```bash
cnn_age_reg_image/
├── cnn_age_reg_image.ipynb # Main Jupyter notebook
└── README.md # Project documentation
```
---

## 🚀 Features

- Image loading and preprocessing
- Custom CNN architecture using Keras
- Age regression using Mean Squared Error (MSE) loss
- Visualizations for training performance
- Age prediction from test images

---

## 🛠️ Tech Stack

- Python 3.x  
- TensorFlow / Keras  
- NumPy, Matplotlib

---

## ▶️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/cnn-age-reg-image.git
cd cnn-age-reg-image
```


### 2. Install Dependencies
It's recommended to use a virtual environment.


### 3. Run the Notebook

```bash
jupyter notebook cnn_age_reg_image.ipynb
```

---

## 📦 Dataset
I used [Pgu-Face: A dataset of partially covered facial images](https://pmc.ncbi.nlm.nih.gov/articles/PMC5024140/).

---

## 📊 Output
The model predicts approximate ages from input images. You’ll also see plots for training loss and visual results of predicted vs. actual ages.

---

## 🧠 Lessons Learned
Basics of CNN architecture

Regression using deep learning

Importance of preprocessing and dataset quality

How training performance varies with model depth

---

## 📌 Future Ideas
Switch to a pre-trained model like MobileNetV2 or ResNet

Add data augmentation

Deploy with a simple Flask or Streamlit web app

---

## 👤 Author
Alireza Kalantarhormozi
GitHub: @alirezakalantarhormozi
