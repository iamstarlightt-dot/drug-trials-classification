# Drug Trials Classification Model – TCS iON RIOI Project

## 📌 Project Overview
This project builds a **machine learning classification model** to predict the **side effects** of a drug trial based on:
- Age
- Gender
- Race

The dataset is **synthetically generated** using Python's `Faker` library to simulate 400,000 patient records, as per the TCS iON RIOI project requirements.

---

## 🎯 Objectives
1. Generate a dataset of 400,000 patients containing:
   - Name
   - Age
   - Gender
   - Race
   - Side Effects
2. Clean and preprocess the dataset.
3. Train and test a classification model.
4. Evaluate model accuracy and effectiveness.
5. Visualize results using:
   - Confusion Matrix
   - Feature Importance Chart
6. Save & load the trained model for future use.
7. Allow interactive predictions from user input.

---

## 🛠️ Tools & Libraries Used
- Python (Google Colab)
- Pandas
- Faker
- Scikit-learn
- Matplotlib / Seaborn
- Joblib

---

## 📂 Folder Structure
drug-trials-classification/
│
├── dataset/
│ └── drug_trials_dataset.csv
│
├── models/
│ ├── drug_side_effects_model.pkl
│ ├── le_gender.pkl
│ ├── le_race.pkl
│ └── le_side_effects.pkl
│
├── notebook/
│ └── Drug_Trials_Classification_Project.ipynb
│
└── README.md

---

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/iamstarlightt-dot/drug-trials-classification.git
   cd drug-trials-classification
