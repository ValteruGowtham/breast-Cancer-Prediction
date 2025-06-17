
# 🩺 Breast Cancer Prediction using Logistic Regression

This project uses **Logistic Regression** to classify whether a tumor is **benign (0)** or **malignant (1)** based on features from the **Wisconsin Breast Cancer dataset**.

---

## 📂 Dataset

- Source: `sklearn.datasets.load_breast_cancer`
- 30 numeric features extracted from tumor images
- Binary target: 0 (Benign), 1 (Malignant)

---

## 🧪 Techniques Used

- Data preprocessing (label encoding, feature scaling)
- Hyperparameter tuning with `GridSearchCV`
- Model evaluation (confusion matrix, classification report, ROC-AUC)
- Feature importance analysis
- Model export with `joblib`

---

## 📈 Results

- Achieved **high accuracy** and **AUC score**
- Best parameters chosen with 5-fold cross-validation
- Model saved and ready for deployment

---

## 💻 Run This Project

1. Clone this repo:
   ```bash
   git clone https://github.com/your-username/breast-cancer-prediction.git
   cd breast-cancer-prediction

2. Install required packages:
   ```bash
   pip install -r requirements.txt

3. Run the model:
   ```bash
   python code.py

## Model Export:
   ```bash
   logistic_model.pkl
