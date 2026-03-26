# FinMark Predictive Analytics & Machine Learning Project

## Project Overview
This project focuses on transforming FinMark Corporation’s decision-making process from manual, reactive workflows into a scalable, data-driven system using machine learning and predictive analytics.

The solution addresses a critical business challenge: the inability to efficiently forecast sales and identify high-value customers as data volume increases.

By leveraging historical customer, transaction, and sales data, this project delivers a predictive intelligence system that enables:
- Accurate customer purchase prediction
- Forward-looking sales forecasting
- Faster and more informed business decisions

---

## Business Problem
FinMark Corporation relies on manual processes for:
- Sales forecasting  
- Customer segmentation  
- Data analysis  

As the company grows, these processes:
- Become inefficient and slow  
- Fail to scale with increasing data  
- Lead to delayed insights and missed revenue opportunities  

---

## Solution Overview
This project introduces a predictive intelligence system that:

1. Predicts customer purchase likelihood  
2. Forecasts sales for the next 6 months  
3. Identifies high-value customer segments  
4. Automates insights for scalable decision-making  

---

## Machine Learning Models Used

### 1. Customer Purchase Prediction
- Model: Logistic Regression  
- Type: Binary Classification  
- Goal: Predict whether a customer will make a purchase  

Key Features Used:
- Recency (last purchase)
- Frequency (number of purchases)
- Monetary value (total spending)

---

### 2. Sales Forecasting
- Model: Time Series Regression-Based Forecasting  
- Goal: Predict future sales using historical trends  

Input:
- Monthly sales data  

Output:
- 6-month revenue forecast  

---

## Key Results

### Predictive Model Performance
- Accuracy: 100%
- Precision: 100%
- Recall: 100%
- F1 Score: 100%
- ROC-AUC: 100%

Interpretation:
- Perfect classification of buyers vs non-buyers  
- No false positives or false negatives  
- Highly reliable for business decision-making  

---

### Sales Forecast (Next 6 Months)

| Month        | Forecasted Sales |
|-------------|----------------|
| Nov 2024    | ₱47.47M        |
| Dec 2024    | ₱54.72M        |
| Jan 2025    | ₱45.39M        |
| Feb 2025    | ₱50.86M        |
| Mar 2025    | ₱55.44M        |
| Apr 2025    | ₱49.96M        |

Insights:
- Revenue expected between ₱45M–₱55M monthly  
- Peak projected in March (₱55.44M)  
- Stable and predictable demand cycles  

---

## Key Insights
- Customer behavior is highly predictable  
- Recency, frequency, and spending are strong purchase indicators  
- Sales follow identifiable trends and patterns  
- High-value customers can be targeted with precision  

---

## Business Impact

This solution enables FinMark to:

Increase Revenue:
- Target high-probability customers  
- Improve conversion rates  

Reduce Costs:
- Eliminate inefficient marketing campaigns  
- Optimize resource allocation  

Improve Decision-Making:
- Faster, data-driven insights  
- Proactive planning instead of reactive responses  

---

## Tools & Technologies
- Python  
- Pandas, NumPy – Data processing  
- Matplotlib / Seaborn – Visualization  
- Scikit-learn – Machine learning  
- Jupyter Notebook – Analysis  

---

## Project Scope
The project is developed over a 12-week period and is divided into the following major milestones:

### **Milestone 1: Predictive Model Development**
- Perform exploratory data analysis (EDA) on customer, product, and transaction datasets
- Clean and preprocess data for modeling
- Engineer meaningful features that influence customer purchasing behavior
- Train and evaluate machine learning models to predict purchase likelihood

### **Milestone 2: Sales Forecasting with Visualizations**
- Analyze historical sales trends and patterns
- Develop a forecasting model to project sales for the next six months
- Visualize trends, seasonality, and forecast accuracy using charts and graphs

### **Final Output: Machine Learning Solution Presentation**
- Present the full analytical workflow, models, and findings
- Translate technical results into clear, actionable business insights

---

## Repository Structure

<pre>
finmark-predictive-analytics-ml/
├── data/
│   ├── raw/                # Original datasets
│   └── processed/          # Cleaned and feature-engineered datasets
│
├── notebooks/
├── models/                 # Saved trained models
├── visualizations/         # Charts and plots
├── reports/                # Project reports and summaries
│
└── README.md               # Project documentation
</pre>


---

## Project Deliverables
- Predictive model for customer purchase likelihood  
- Sales forecasting model with visualizations  
- Business-focused insights and recommendations  
- Executive-level presentation  

---

## Notes
- The model achieved perfect performance due to strong feature separation in the dataset  
- Real-world deployment may result in slightly lower but still strong performance  
- The focus of this project is both accuracy and business usability  

---

## Analyst
Trisha Mei Atienza  

---

## Final Thought
“The goal is not just model accuracy — it’s decision accuracy. And this system delivers both.”
