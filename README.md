# 📊 Marketing Revenue Prediction using Machine Learning

## 📌 Project Overview
Marketing campaigns generate a large amount of data, but predicting revenue from these campaigns is not straightforward.  
This project was developed to understand how different marketing factors influence revenue and to build a machine learning model that can predict revenue effectively.

---

## 📊 Dataset Information
- **Dataset Name:** Marketing and Product Performance Dataset  
- **Source:** https://www.kaggle.com/datasets/imranalishahh/marketing-and-product-performance-dataset  
- **Type:** Structured tabular dataset  
- **Target Variable:** Revenue_Generated  

---

## 🛠️ Methodology & Model
This is a supervised machine learning regression problem.

### 🔹 Data Preprocessing
- Removed unnecessary ID columns (Campaign_ID, Product_ID, Customer_ID)
- Selected relevant numerical features
- Cleaned the dataset for better model performance

### 🔹 Model Used
- Linear Regression

### 🔹 Evaluation Metrics
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

## 🚀 How to Run the Code
1. Download or clone this repository  
2. Install required libraries using:
 pip install -r requirements.txt
3. Download the dataset from the Kaggle link above  
4. Place the dataset file in the same folder as the notebook  
5. Open `notebook.ipynb` and run all cells  

---

## 📈 Results & Insights
- The model was able to predict revenue with reasonable accuracy  
- Features such as **conversions and ROI** were found to have a strong impact on revenue  
- A comparison between actual and predicted values is visualized using a scatter plot  

---

## 🧠 Tools Used
- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- Matplotlib  

---

## 🎯 Conclusion
This project demonstrates how machine learning can be used to analyze marketing performance and predict revenue.  
Such insights can help businesses make better data-driven decisions.
