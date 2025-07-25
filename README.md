# On-Time, Every-Time: Predicting E-Commerce Delivery Delays with ML 🚚📉

This project uses machine learning to predict whether an order will be delivered late or on time, based on historical delivery data.

## 📌 Problem Statement
Late deliveries affect customer experience and business performance. We build a model to classify orders as "Late" or "On-Time."

## 🧰 Tools & Technologies
- Python (Pandas, Scikit-learn, Seaborn, Matplotlib)
- Jupyter Notebook
- Random Forest, Logistic Regression, XGBoost

## 📊 Workflow
1. Data Cleaning & Preprocessing
2. Feature Engineering
3. Model Training & Evaluation
4. Visualization of Key Features

## 🔍 Key Insight
Random Forest achieved 68% accuracy and identified vendor and distance as top delay predictors.

## 📁 Files Included
- Jupyter notebook (`delivery_delay_prediction.ipynb`)
- Cleaned dataset
- Visuals (confusion matrix, feature importance)
- Trained model (`.pkl` file)

## 📦 How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebooks/delivery_delay_prediction.ipynb
