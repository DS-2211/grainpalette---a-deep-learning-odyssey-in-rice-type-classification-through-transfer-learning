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
| [`backend-flask/`](./backend-flask) | Flask API to load model, handle uploads, and return predictions |
| [`frontend-templates/`](./frontend-templates) | HTML-based UI for image upload and results display |
| [`model-training/`](./model-training) | Jupyter Notebook + Python script for data processing, training, and evaluation |
| [`results/`](./results) | Accuracy/loss plots, confusion matrix, UI screenshots |
| [`video-demo/`](./video-demo) | Demo walkthrough video |
| [`training-dataset/`](./training-dataset) | Dataset or structure for rice image categories |
| [`README.md`](./README.md) | This file |


---

## 🚀 Demo Video

Watch the full walkthrough here:  
🎥 **[Rice Grain Classifier – Demo]([https://youtu.be/your-demo-link](https://drive.google.com/file/d/1VML8l14Xu-J0RRLRPRxJ8EESaH7wMw9S/view?usp=sharing))**

---

## 🛠 Tech Stack

- **Frameworks**: TensorFlow 2.x, Keras, Flask
- **Model**: MobileNetV2 (from `keras.applications`)
- **Frontend**: HTML, CSS, JS (via Flask templating)
- **Visualization**: Matplotlib, Seaborn, Plotly
- **Dataset**: [Rice Image Dataset (Kaggle)](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset)

---
