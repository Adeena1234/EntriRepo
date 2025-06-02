# 📈 Capstone Project: Credit Risk Prediction, Customer Segmentation & Default Rate Forecasting
Welcome to a comprehensive machine learning and business intelligence project that integrates advanced analytics, real-world financial data, and professional visualization for smarter credit decision-making.

This capstone project focuses on analyzing credit risk using supervised learning, segmenting customers with unsupervised learning, and forecasting default rates. It combines Machine Learning and Business Intelligence (Power BI) to support better decision-making in finance.


#  🔎 Objective
This project addresses three critical problems in modern finance:

**Credit Risk Prediction**: Identify whether a loan applicant is likely to default or not.

**Customer Segmentation**: Group customers into meaningful segments based on financial behavior using clustering.

**Default Rate Forecasting**: Predict future default rates to improve portfolio planning and risk management.

To bridge the gap between analytics and business understanding, the project also includes Power BI dashboards for interactive visualization.

# 📅 Dataset

**Source**: Home Credit Risk dataset (Kaggle)

**Size:** ~300,000 records

**Key Features:** AMT_INCOME_TOTAL, AMT_CREDIT, DAYS_BIRTH, DAYS_EMPLOYED, TARGET (Default: 1 = Yes, 0 = No)



# 📊 Tools, Technologies & Libraries

**Languages**: Python, DAX (Power BI)

**ML Libraries:** scikit-learn, pandas, numpy, matplotlib, seaborn, xgboost

**Business Intelligence:** Power BI for visualization


# 🔄 Workflow

**1. Data Preprocessing**

Null handling, encoding, feature selection

Scaling for clustering and model training

**2. Customer Segmentation (K-Means Clustering) (Unsupervised)**

- Scaled financial features and applied PCA for visualization.
- Segments customers into 4 clusters.

Elbow method to determine k

Result: 4 distinct customer segments visualized via PCA

**3. Credit Risk Prediction (Supervised Learning)**

Models Used: Logistic Regression

Random Forest (Best: 91.97% Accuracy)

Gradient Boosting, SVM, KNN, Naive Bayes, MLP

Evaluation:

Classification Report

Confusion Matrix

Feature Importance Charts

Random Forest performed best due to its robustness and ability to handle feature importance and class imbalance.


**4. Default Rate Forecasting**

Time-based analysis

Forecasting future default trends

Visualized with line charts

**5. Power BI Visualization**

Exported clean data from Python

Power BI was used to build visual dashboards:

Built visuals:

🌀 Tree Map: Customer Segments

📊 Bar Chart: Income Segment vs Risk

🌍 Line Chart: Default Rate Over Time

🔹 Pie Chart: Default Status

Power BI visuals were exported using `Power BI Publish to Web` and embedded in Jupyter Notebook via `IFrame`.


# 📊 Results

| Model               | Accuracy | Use Case                          |
| ------------------- | -------- | --------------------------------- |
| ✨ Random Forest     | **91.97%**  | Best overall performance          |
| Gradient Boosting   | 83%      | Excellent but more complex        |
| Logistic Regression | 76%      | Fast, interpretable baseline      |
| MLP Neural Network  | 80%      | Deep learning approach            |
| SVM                 | 79%      | Sensitive to scaling              |
| KNN                 | 73%      | Simple, lower accuracy            |
| Naive Bayes         | 68%      | Fast, less effective on this data |


# 📊 Business Insights

**High Income != Low Risk**: Some high-income customers still default.
**Segment Targeting**: Certain customer clusters show higher default rates.
**Time Trends**: Default rates vary seasonally; predictive insights help in planning.

# ✨ Key Features

* Modular Jupyter Notebooks
* Model Comparison and Selection
* BI Dashboard for Non-Technical Users
* Clear code documentation and export paths


# 🚀 How to Run

 **Clone repository** 
git clone https://github.com/Adeena1234/EntriRepo/blob/main/Final_Project_Test.ipynb

**Open in Jupyter**
jupyter notebook


# 📢 Conclusion


This capstone project successfully demonstrates the integration of machine learning and business intelligence to address critical challenges in the finance domain. By combining credit risk prediction, customer segmentation, and default rate forecasting, the project enables financial institutions to:

Identify high-risk customers using accurate predictive models like Random Forest.

Segment customers based on financial behavior using K-Means Clustering.

Forecast potential default rates for better risk management.

Visualize actionable insights using Power BI, helping stakeholders make informed, data-driven decisions.

This end-to-end pipeline highlights the power of combining supervised and unsupervised learning with BI tools, making it a valuable reference for real-world financial analytics and credit scoring systems.
