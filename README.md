# 🌾 GrainPalette – A Deep Learning Odyssey in Rice Type Classification

A computer vision project using **Transfer Learning with MobileNetV2** to classify five rice grain types—**Arborio, Basmati, Ipsala, Jasmine, and Karacadag**—with over 92% accuracy.  
This repo includes everything from model training and evaluation to an end-to-end web demo built with Flask.

---

## 📌 Project Highlights

- ✅ **Transfer Learning** using MobileNetV2 pretrained on ImageNet
- 📊 Accuracy: ~97% on training, ~92% on validation
- 🧠 5-Class Image Classification on grain-level images
- 🧪 Trained on 3,000 images across 5 categories
- 💻 Flask-based demo with image upload and prediction
- 📈 Evaluation via accuracy plots, confusion matrix, and test predictions

---

## 🗂 Repository Structure

| Folder | Description |
|--------|-------------|
| [`Backend (Flask)/`](./Backend (Flask)) | Flask API to load model, handle uploads, and return predictions |
| [`Frontend (templates)/`](./Frontend (templates)) | HTML-based UI for image upload and results display |
| [`Model Training/`](./Model_Training) | Jupyter Notebook + Python script for data processing, training, and evaluation |
| [`Results/`](./Results) | Accuracy/loss plots, confusion matrix, UI screenshots |
| [`Video Demo/`](./Video_Demo) | Demo walkthrough video |
| [`Training Dataset/`](./Training_Dataset) | Link to dataset or sample structure (if large) |
| [`README.md`](./README.md) | This file |

---

## 🚀 Demo Video

Watch the full walkthrough here:  
🎥 **[Rice Grain Classifier – YouTube Demo](https://youtu.be/your-demo-link)**

---

## 🛠 Tech Stack

- **Frameworks**: TensorFlow 2.x, Keras, Flask
- **Model**: MobileNetV2 (from `keras.applications`)
- **Frontend**: HTML, CSS, JS (via Flask templating)
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Dataset**: [Rice Image Dataset (Kaggle)](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset)

---
