# 📊 Sales Prediction Using Python

### 🎯 Project Overview
This project focuses on **predicting product sales** based on **advertising expenditure** across three major media channels — **TV, Radio, and Newspaper**.  
It applies **machine learning regression models** to analyze how marketing budgets influence sales outcomes and determine which advertising medium contributes the most to increasing revenue.

The dataset used is the classic **Advertising.csv**, which includes spending data and corresponding product sales.

---

## 🧠 Objective
- Build a **Simple Linear Regression model**.
- Extend to **Multiple Linear Regression**, **Random Forest**, and **XGBoost** for accuracy comparison.
- Identify which advertising channels have the greatest impact on product sales.
- Evaluate model performance using metrics like **R² Score**, **RMSE**, and **MAE**.

---

## 🧩 Dataset
- **Columns:**  
  - `TV`: Advertising spend on TV (in thousands of dollars)  
  - `Radio`: Advertising spend on Radio (in thousands of dollars)  
  - `Newspaper`: Advertising spend on Newspaper (in thousands of dollars)  
  - `Sales`: Corresponding sales (in thousands of units)

---

## ⚙️ Technologies Used
- **Programming Language:** Python  
- **Libraries:**
  - `pandas`, `numpy` – Data handling and preprocessing  
  - `matplotlib`, `seaborn` – Data visualization and insights  
  - `scikit-learn` – Machine learning models and metrics  
  - `xgboost` – Gradient boosting regression  
  - `joblib` – Model saving and serialization

---

## 🔍 Exploratory Data Analysis (EDA)
EDA helped identify relationships between sales and advertisement spending:

- Strong **positive correlation** between **TV advertising** and **sales**.
- **Radio** also shows a positive effect, though slightly weaker.
- **Newspaper** contributes minimally to sales increase.
- Pair plots and heatmaps were used to visualize feature correlations.

---

## 🤖 Model Development
Four regression models were trained and compared:

| Model | Features | R² Score | RMSE | Remarks |
|--------|-----------|----------|------|----------|
| Simple Linear Regression | TV only | 0.803 | 2.47 | Baseline model |
| Multiple Linear Regression | TV, Radio, Newspaper | 0.906 | 1.32 | Good improvement |
| Random Forest Regressor | All features | ~0.94 | - | Non-linear modeling |
| XGBoost Regressor | All features | **~0.95** | - | Best performer |

✅ **Best Model:** XGBoost Regressor

---

## 📈 Key Insights
- **TV advertising** has the strongest impact on sales.  
- **Radio** contributes significantly when combined with TV.  
- **Newspaper** advertising shows very little influence on sales.  
- Ensemble models (Random Forest, XGBoost) effectively capture complex relationships between marketing channels.  

---

## 🏁 Conclusion
- The **Simple Linear Regression** model serves as a good baseline with 80% accuracy.  
- **Multiple Linear Regression** improves accuracy to about 90%.  
- **XGBoost** achieves the best performance (~95% R²), demonstrating the advantage of advanced ensemble learning.  
- Businesses should **focus their advertising budgets on TV and Radio** for maximum sales impact.

---

## 🚀 Future Enhancements
- Include **digital/online advertising** as new data features.  
- Apply **hyperparameter tuning** for Random Forest and XGBoost.  
- Deploy the model using **Flask or Streamlit** for real-time sales forecasting.  
- Incorporate **cross-validation** for more robust model evaluation.

---

## 📚 Acknowledgment
This project was completed as part of the **CodSoft Data Science Internship (Task 4: Sales Prediction)**, showcasing skills in regression modeling, data visualization, and model interpretation.

---

### 👨‍💻 Author
**[Your Name]**  
Data Science Intern @ CodSoft  
📧 [your.email@example.com]  
🌐 [LinkedIn/GitHub Profile]
# Sales-Prediction-using-python-Task-2-
