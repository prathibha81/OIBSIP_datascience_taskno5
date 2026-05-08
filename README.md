# TASK 1
#  Sales Prediction Using Machine Learning

##  Overview

This project focuses on predicting product sales based on advertising expenditures across different marketing platforms such as TV, Radio, and Newspaper. The goal is to analyze how advertising impacts sales and build a Machine Learning model capable of forecasting future sales accurately.

A Random Forest Regressor model is used to improve prediction accuracy and capture complex relationships between advertising budgets and sales.


#  Problem Statement

The objective of this project is to build a Machine Learning model that predicts product sales based on advertising expenditure across different platforms such as TV, Radio, and Newspaper. The model helps businesses analyze the impact of advertising on sales and make data-driven marketing decisions.



#  Objective

- Predict future sales using advertising data
- Analyze the impact of different advertising platforms
- Improve prediction accuracy using Machine Learning
- Help businesses optimize marketing strategies



#  Dataset Information

| Column Name | Description |
|------------|-------------|
| TV | Advertising budget spent on TV |
| Radio | Advertising budget spent on Radio |
| Newspaper | Advertising budget spent on Newspaper |
| Sales | Product sales value |


# ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
  

#  Machine Learning Model Used

## Random Forest Regressor

Random Forest is an ensemble learning algorithm that combines multiple decision trees to improve prediction accuracy and reduce overfitting.

### Why Random Forest?
- High prediction accuracy
- Handles non-linear relationships
- Reduces overfitting
- Works efficiently on numerical datasets


# 🧹 Data Preprocessing

The following preprocessing steps were performed:

- Checked missing values
- Removed duplicates
- Verified data types
  

#  Data Visualization

Visualization techniques were used to understand relationships between variables:

- Scatter plots
- Correlation heatmap
- Feature importance analysis

---

#  Model Training

The dataset was divided into:
- 80% Training Data
- 20% Testing Data

The Random Forest model was trained using:

```python
RandomForestRegressor(
    n_estimators=300,
    random_state=42
)
```



# Model Evaluation

The model performance was evaluated using:

- R² Score : 0.9826351706404014
- Mean Squared Error (MSE) : 0.5480964194444423
- Root Mean Squared Error (RMSE) : 0.740335342560682

### Sample Results

| Metric | Value |
|--------|------|
| R² Score | High Accuracy |
| RMSE | Low Error |



# 📌 Project Workflow

1. Import Libraries  
2. Load Dataset  
3. Data Cleaning  
4. Data Visualization   
5. Train-Test Split  
6. Model Training  
7. Prediction  
8. Model Evaluation  


# Sample Prediction

### Input:
- TV = 100
- Radio = 20
- Newspaper = 10

### Output:

```python
Predicted Sales = 11.872
```

---

#  Real-World Applications

- Marketing Budget Optimization
- Business Sales Forecasting
- Advertisement Performance Analysis
- Revenue Growth Strategy

---

#  Requirements

Create a `requirements.txt` file with:

```txt
pandas
numpy
matplotlib
scikit-learn
```

---

# ▶️ How to Run the Project

## 1️⃣ Clone Repository

```bash
git clone <https://github.com/prathibha81/OIBSIP_datascience_taskno5.git>
```

## 2️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

## 3️⃣ Run Notebook

Open Jupyter Notebook and execute all cells.

---

# 📌 Future Improvements

- Deploy model using Flask or Streamlit
- Use XGBoost for better accuracy
- Add real-time prediction interface
- Hyperparameter tuning

---

# 🧠 Conclusion

This project successfully demonstrates how Machine Learning can be used to predict sales based on advertising expenditure. The Random Forest model achieved strong predictive performance and provided valuable insights into the impact of advertising channels on sales.

---

# 👩‍💻 Author

Prathibha U
