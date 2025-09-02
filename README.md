# 🕺 Human Action Detection

This project focuses on classifying human activities (such as walking, jogging, sitting, etc.) from time-series accelerometer data. It applies machine learning models to predict human actions using sensor signals.

---

## 📌 Project Workflow
- **Exploratory Data Analysis (EDA):** Visualized and understood distributions, correlations, and trends in accelerometer signals.
- **Preprocessing:**
  - Scaling using `StandardScaler` and `RobustScaler`
  - Encoding categorical labels
  - Handling class imbalance via resampling
- **Model Training:**
  - Trained multiple ML models: Logistic Regression, KNN, Decision Tree.
  - Hyperparameter tuning using `GridSearchCV`
- **Evaluation:**
  - Metrics: Accuracy, Precision, Recall, F1-Score
  - Best model achieved **96.91% accuracy, 96.74% precision, 95.84% recall, 96.28%  F1-score**

---

## ⚙️ Tech Stack
- **Programming Language:** Python  
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Statsmodels  

---

## 📊 Results
The project demonstrates how different supervised learning models perform on time-series classification.  
The KNN model outperformed other algorithms with 96.7% accuracy on the test set, making it highly reliable for classifying human actions from sensor data.

---

## 📂 Dataset
The dataset used is from Kaggle: [Human Activity Recognition](https://www.kaggle.com/datasets/die9origephit/human-activity-recognition).  

⚠️ **Note:** The dataset is licensed as **Other (specified in description)** and cannot be redistributed.  

- Please download it directly from Kaggle.  
- Place the file `time_series_data_human_activities.csv` inside the `data/` folder before running the notebook.  

---

## 🚀 How to Run

1. Clone the repository  
   ```bash
   git clone https://github.com/a02s04/Human_Action_Detection.git
   cd Human_Action_Detection

2. Install the depenedencies
   ```bash
   pip install -r requirements.txt

3. Run the notebook
   ```bash
   jupyter notebook Human_Action_Detection.ipynb



