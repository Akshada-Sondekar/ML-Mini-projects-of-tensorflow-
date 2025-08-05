# 🔐 Network Intrusion Detection using UNSW-NB15 Dataset

A machine learning-based solution to detect network intrusions using the UNSW-NB15 dataset. This project uses Random Forest for classification.

---

## 📁 Dataset

- **Source**: [Kaggle - UNSW-NB15](https://www.kaggle.com/datasets/mrwellsdavid/unsw-nb15)
- **Files Used**: `UNSW_NB15_training-set.csv`
- **Target**: `label` column → `0: Normal`, `1: Attack`

---

## 🔍 Project Flow

### 📌 1. Import Libraries
Used essential libraries for data handling, visualization, preprocessing, and model building.

### 📊 2. Load & Explore Dataset
- Loaded the dataset.
- Checked dataset dimensions and previewed the data.

### 🧹 3. Data Cleaning
- Dropped irrelevant columns (like `id`).
- Checked and handled missing values.

### 🎯 4. Encoding Categorical Data
- Used `LabelEncoder` to convert categorical columns into numeric.

### ⚙️ 5. Feature & Target Separation
- `X` = features
- `y` = target (`label` column)

### 📏 6. Data Scaling & Splitting
- Applied `StandardScaler`.
- Split dataset into 80% training and 20% testing.

### 🤖 7. Model Training
- Used **Random Forest Classifier** for its robustness and performance.

### 📈 8. Evaluation
- Evaluated using **Accuracy Score**, **Classification Report**, and **Confusion Matrix**.
- Plotted a confusion matrix to visualize performance.

### 🔍 9. Feature Importance
- Visualized top 10 most important features from the Random Forest model.
---

## 🧠 Model Used

- **Random Forest Classifier**
  - Handles imbalanced and high-dimensional data well.
  - Provides feature importance out-of-the-box.

---

## 📌 Future Improvements

- Try advanced models (e.g., XGBoost, LightGBM)
- Deploy using Docker or cloud services

---

## 🧑‍💻 Author

**Akshada Sondekar**  
BCA AIML Student | Machine Learning Enthusiast

---

## ⭐ GitHub Project Tags

`Machine Learning` `Network Security` `Intrusion Detection` `Random Forest` `UNSW NB15` `Streamlit App`

