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


| Folder Name               | Description                                                         |
|---------------------------|---------------------------------------------------------------------|
| Backend (Flask)           | Flask API to load the model, handle image uploads, and return predictions |
| Frontend (templates)      | HTML-based UI for image upload and displaying classification results |
| Model Training            | Jupyter notebooks and scripts for data processing, training, and evaluation |
| Results                   | Accuracy/loss plots, confusion matrix, and UI screenshots           |
| Video Demo                | Demo walkthrough video of the application                           |
| Training Dataset          | Folder showcasing dataset structure or sample images                |
| Document                  | Final project report and documentation                              |
| README.md                 | This file                                                           |




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
