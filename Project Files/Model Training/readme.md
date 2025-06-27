# 🌾 GrainPalette – Model Training & Pre-Trained Weights

This directory contains everything you need to **train** the GrainPalette rice-variety classifier from scratch **or** jump straight to inference with the ready-made model `rice.h5`.

---

## 📂 Contents

| File | Purpose |
|------|---------|
| `RiceClassifier_Training.ipynb`<br>*or* `train_rice_classifier.py` | End-to-end script/notebook that: <br>1. Loads the Rice Image Dataset<br>2. Pre-processes images → 224 × 224<br>3. Splits data 80 / 10 / 10<br>4. Fine-tunes **MobileNetV2**<br>5. Logs accuracy/loss curves, confusion matrix & report<br>6. Saves final weights to `rice.h5` |
| `rice.h5` | Fine-tuned MobileNetV2 model (5-class soft-max) ready for inference or deployment |
| `requirements.txt` | Python dependencies for training & evaluation |

---

## 🗄️ Dataset

- **Source:** [Veronica Morelli – Rice Grain Image Dataset](https://www.kaggle.com/datasets/muratkokludataset/rice-image-dataset)
- 
- **Structure expected:**
- Rice_Image_Dataset/
├── Arborio/
├── Basmati/
├── Ipsala/
├── Jasmine/
└── Karacadag/

> 📌 *Change the `data_dir` path in the first cell to match your local folder.*
