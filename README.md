# 🟡 Gold Price Prediction Using Machine Learning  
### _A Complete End-to-End Data Science & ML Project_

This project builds a **Machine Learning model** to predict **Gold (GLD) prices** using multiple financial indicators such as **SPX**, **USO**, **SLV**, and **EUR/USD**.  
Unlike typical ML demos, this project focuses on **feature analysis**, **correlation understanding**, and **model performance optimization**, making it both educational and industry-relevant.

---

# 📘 Project Highlights

### ✅ Machine Learning Model  
- **Random Forest Regression**  
- **Model Accuracy (R² Score): _98% (0.98)_**  
- **Mean Absolute Error (MAE): Low (~0.20 – 0.30)**  

### 🎯 Why Random Forest?
Random Forest achieved the **highest accuracy** compared to Linear Regression and Decision Tree models and handled **non-linear relationships** present in financial data exceptionally well.

---

# 📂 Dataset & Features

### Dataset Source  
- Local CSV file: `gld_price_data.csv`  
- Total Records: **2290 rows**  
- Columns: **6**

### 📊 Features Used for Prediction (Independent Variables)

| Feature | Description |
|--------|-------------|
| **SPX** | S&P 500 Index |
| **USO** | Crude Oil Price |
| **SLV** | Silver ETF Price |
| **EUR/USD** | Euro vs US Dollar exchange rate |

### 🎯 Target Variable  
| Target | Description |
|--------|-------------|
| **GLD** | Gold ETF Price (value to be predicted) |

---

# 📈 Feature Correlation Analysis

A correlation heatmap revealed that:

- **GLD has the strongest correlation with SLV (Silver)**  
- SPX shows a moderate correlation  
- EUR/USD & USO show weaker but meaningful correlations  

These insights directly guided **feature selection** and improved model performance.

---

# 🚀 Model Performance Summary

| Metric | Value |
|--------|--------|
| **R² Score** | **0.98 (98% Accuracy)** |
| **MAE** | ~0.20–0.30 |
| **Intercept** | Not applicable (Random Forest) |

🔍 _This accuracy is significantly higher than typical regression models due to Random Forest’s ability to capture non-linear patterns._

---

# 🛠️ Technologies Used

- **Python**
- **NumPy**
- **Pandas**
- **Matplotlib & Seaborn**
- **Scikit-Learn**
- **Jupyter Notebook**

---

# 🧪 End-to-End Workflow (Inside Notebook)

1. Data Import & Inspection  
2. Missing Value Checks  
3. Exploratory Data Analysis  
4. Correlation Heatmap  
5. Feature-Target Splitting  
6. Train-Test Split  
7. Model Training (Random Forest)  
8. Evaluation & Accuracy Metrics  
9. Predicting Gold Price for Sample Inputs  

---

# 🖥️ Run This Project on Your Local Machine

Follow these steps exactly to run the project without issues:
1. Create a Virtual Environment (Recommended)
   python -m venv venv

   .**Windows**
        venv\Scripts\activate
   .**Mac**
        source venv/bin/activate
2. Install Required Libraries
   pip install numpy pandas matplotlib seaborn scikit-learn jupyter
3. Launch Jupyter Notebook
    jupyter notebook

    open:
    Gold_Price_Prediction.ipynb
4. Run All Cells
    Click Kernel → Restart & Run All to execute the entire ML pipeline.
---

