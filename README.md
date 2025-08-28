# 🌧️ Rainfall Prediction in Australia using Machine Learning

This project predicts whether it will rain tomorrow in Australia using **historical weather data** and various **machine learning algorithms**. The goal is to assist in weather forecasting and decision-making by analyzing key climate features such as temperature, humidity, wind speed, and pressure.  

---

## 📊 Dataset
- Source: [Rain in Australia Dataset (Kaggle)](https://www.kaggle.com/datasets/jsphyg/weather-dataset-rattle-package)  
- Size: ~145,000 records  
- Features: Temperature, Humidity, Wind Speed, Rainfall, Pressure, Cloud Cover, etc.  
- Target: `RainTomorrow` (Yes/No)  

---

## 🔧 Features & Workflow
1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical features
   - Feature scaling  

2. **Exploratory Data Analysis (EDA)**
   - Correlation heatmaps  
   - Distribution plots  
   - Weather pattern insights  

3. **Machine Learning Models**
   - Logistic Regression  
   - Decision Tree Classifier  
   - Random Forest Classifier  
   - Support Vector Machine (SVM)  

4. **Evaluation Metrics**
   - Accuracy  
   - Precision, Recall, F1-score  
   - ROC-AUC curve  

---

## 🚀 Results
- Best model achieved **~85% accuracy** on the test set  
- **Random Forest** performed the best with balanced precision and recall  

---

## 📂 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  

---

## ▶️ How to Run
1. Clone this repository  
   ```bash
   git clone https://github.com/username/Rainfall-Prediction-Australia.git
