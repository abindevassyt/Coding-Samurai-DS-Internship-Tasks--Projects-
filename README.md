# 🥋 Data Science Internship Portfolio - Coding Samurai

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Status](https://img.shields.io/badge/Status-Completed-success)
![Focus](https://img.shields.io/badge/Focus-Data%20Science%20%26%20ML-orange)

## 📜 Overview
Welcome to my submission for the **Coding Samurai Data Science Internship**. 
This repository contains **6 completed projects** spanning three difficulty levels, covering Data Analytics, Machine Learning (Regression & Classification), Time Series Forecasting, and Natural Language Processing (NLP).

Each project includes a dedicated notebook, dataset, and professional visualizations.

---

## 🛠️ Tech Stack
- **Languages:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn, Statsmodels, NLTK, TextBlob, yfinance.
- **Tools:** Jupyter Notebook, Git.

---

## 📂 Project Structure

| Level | Project Name | Type | Key Technique | Status |
| :--- | :--- | :--- | :--- | :--- |
| **Level 1** | [Superstore Sales Analysis](#project-1-superstore-sales-analysis) | Analytics | EDA & Visualization | ✅ |
| **Level 1** | [Ad Sales Prediction](#project-2-linear-regression-ad-sales) | Regression | Linear Regression | ✅ |
| **Level 2** | [Titanic EDA](#project-3-titanic-exploratory-data-analysis) | Analytics | Multivariate Analysis | ✅ |
| **Level 2** | [Titanic Survival Prediction](#project-4-titanic-survival-prediction-ml) | Classification | Logistic Regression | ✅ |
| **Level 3** | [Stock Price Forecasting](#project-5-stock-price-forecasting) | Time Series | ARIMA | ✅ |
| **Level 3** | [Sentiment Analysis](#project-6-sentiment-analysis-on-social-media) | NLP | Naive Bayes / TF-IDF | ✅ |

---

## 📊 Project Details

### **Level 1: Beginner**

#### [Project 1: Superstore Sales Analysis](./Level 1/Project 1)
**Goal:** Analyze retail data to identify profit/loss patterns and regional trends.
- **Key Insight:** The "Tables" sub-category is generating significant losses due to high discounts, despite having decent sales volume. The West region leads in profitability.
- **Visuals:** Bar charts, Pie charts, Profit Heatmaps.

#### [Project 2: Linear Regression (Ad Sales)](./Level 1/Project 2)
**Goal:** Predict sales revenue based on advertising budgets (TV, Radio, Newspaper).
- **Model:** Multiple Linear Regression.
- **Results:** - **R² Score:** 0.90 (High Accuracy).
    - **Insight:** While TV ads correlate most with sales, Radio ads proved to be highly efficient per dollar spent.

---

### **Level 2: Intermediate**

#### [Project 3: Titanic Exploratory Data Analysis](./Level 2/Project 1)
**Goal:** Perform deep EDA on passenger demographics to understand survival factors.
- **Techniques:** Missing value imputation (Age), Feature Engineering (Family Size).
- **Key Insight:** Validated the "Women and Children First" protocol—Females had a ~74% survival rate compared to ~18% for Males.

#### [Project 4: Titanic Survival Prediction (ML)](./Level 2/Project 2)
**Goal:** Build a Machine Learning model to classify passengers as "Survived" or "Deceased".
- **Model:** Logistic Regression with 10-Fold Cross-Validation.
- **Results:**
    - **Accuracy:** ~81%.
    - **Evaluation:** Confusion Matrix & ROC Curve analysis showing strong sensitivity.

---

### **Level 3: Advanced**

#### [Project 5: Stock Price Forecasting](./Level 3/Project 1)
**Goal:** Forecast future stock prices for Apple (AAPL) using historical data.
- **Data Source:** Real-time data via `yfinance` API.
- **Model:** ARIMA (AutoRegressive Integrated Moving Average).
- **Advanced Analysis:**
    - Stationarity Check (Augmented Dickey-Fuller Test).
    - Time Series Decomposition (Trend, Seasonality, Noise).
- **Result:** Successfully generated a 30-day future price trend.

#### [Project 6: Sentiment Analysis on Social Media](./Level 3/Project 2)
**Goal:** Analyze 14,000+ tweets to detect customer sentiment towards US Airlines.
- **Techniques:** Text Cleaning (Regex), TF-IDF Vectorization, Naive Bayes Classifier.
- **Results:**
    - **Accuracy:** 78%.
    - **Business Intel:** "Customer Service" and "Late Flight" were identified as the primary drivers of negative sentiment.

---
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/YOUR_USERNAME/CODING-SAMURAI-INTERNSHIP-TASK.git](https://github.com/YOUR_USERNAME/CODING-SAMURAI-INTERNSHIP-TASK.git)

   
2. **Install dependencies:**
  '''Bash
  pip install pandas numpy matplotlib seaborn scikit-learn statsmodels yfinance textblob wordcloud
  pip install pandas numpy matplotlib seaborn scikit-learn statsmodels yfinance textblob wordcloud


3. **Navigate to a project folder:**
  '''Bash
  cd Level1/Project1_Superstore_Sales_Analysis

4. **Run the Notebook:**
  '''Bash
  jupyter notebook
