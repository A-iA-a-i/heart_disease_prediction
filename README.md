# Heart Disease Prediction 🫀

This project is a machine learning-based model that predicts the presence of heart disease based on clinical and demographic data. It is intended for educational purposes and as a demonstration of applied data science and classification techniques.

---

## 📊 Dataset

The dataset used in this project is the (https://www.kaggle.com/datasets/fedesoriano/heart-failure-prediction), which contains various features such as:

- Age: age of the patient [years]
- Sex: sex of the patient [M: Male, F: Female]
- ChestPainType: chest pain type [TA: Typical Angina, ATA: Atypical Angina, NAP: Non-Anginal Pain, ASY: Asymptomatic]
- RestingBP: resting blood pressure [mm Hg]
- Cholesterol: serum cholesterol [mm/dl]
- FastingBS: fasting blood sugar [1: if FastingBS > 120 mg/dl, 0: otherwise]
- RestingECG: resting electrocardiogram results [Normal: Normal, ST: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV), LVH: showing probable or definite left ventricular hypertrophy by Estes' criteria]
- MaxHR: maximum heart rate achieved [Numeric value between 60 and 202]
- ExerciseAngina: exercise-induced angina [Y: Yes, N: No]
- Oldpeak: oldpeak = ST [Numeric value measured in depression]
- ST_Slope: the slope of the peak exercise ST segment [Up: upsloping, Flat: flat, Down: downsloping]
- HeartDisease: output class [1: heart disease, 0: Normal]

---

## 🧠 Model Overview

The following steps were taken in this project:

1. **Data Cleaning & Preprocessing**
2. **Exploratory Data Analysis (EDA)**
3. **Feature Selection**
4. **Model Training** using:
   - Decision Tree Classifier
   - KNeighbors Classifier
   - Support Vector Machine (SVM)
5. **Model Evaluation** with accuracy, precision, recall, F1-score, and ROC-AUC

---

## 📁 Project Structure

```bash
heart_disease_prediction/
├── data/
│   └── heart_info.csv
│   └── processed_heart_info.csv
├── models/
│   └── knn.pkl
│   └── svm.pkl
│   └── tree.pkl
├── data_preparation.ipynb
├── decision_tree.ipynb
├── knn.ipynb
├── svm.ipynb
├── requirements.txt
└── README.md
```

---

## 🔧 Installation

1.Clone the repo:
    git clone https://github.com/A-iA-a-i/heart_disease_prediction.git cd heart_disease_prediction
2.Install dependencies:
    pip install -r requirements.txt

---

## 📈 Results

**Decision Tree Classifier**
    - Train Accuracy: ~88%
    - Cross Validation Accuracy: ~89%
    - Test Accuracy: ~85%
**KNeighbors Classifier**
    - Train Accuracy: ~87%
    - Cross Validation Accuracy: ~91%
    - Test Accuracy: ~88%
**Support Vector Machine (SVM)**
    - Train Accuracy: ~87%
    - Cross Validation Accuracy: ~88%
    - Test Accuracy: ~88%