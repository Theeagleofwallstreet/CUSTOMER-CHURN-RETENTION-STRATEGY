# CUSTOMER-CHURN-RETENTION-STRATEGY
# CUSTOMER-CHURN-RETENTION-STRATEGY
Predictive analytics project from the Boston Consulting Group (BCG) PowerCo virtual experience, focused on reducing customer churn through data-driven insights and machine learning. Demonstrates how customer behavior data can inform strategic business decisions and improve retention.

📖 **Read the Full Case Study on Medium:**  
> Explore the complete breakdown of this project — including business insights, EDA visuals, and strategic impact — in my Medium article:  
> [**Churn2Growth: PowerCo Customer Retention Analytics**](https://medium.com/@theeagleofwallstreet/churn2growth-predicting-customer-retention-for-powerco-a-bcg-data-science-project-4848fd7dc2ab)

---

# ⚡ Churn2Growth: PowerCo Customer Retention Analytics

![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-orange.svg)
![Scikit-learn](https://img.shields.io/badge/ML-Scikit--learn-green.svg)
![Status](https://img.shields.io/badge/Status-Completed-success.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

## 🧠 Project Overview
**Churn2Growth** is a data science project completed as part of the **Boston Consulting Group (BCG) PowerCo Virtual Experience**.  
The objective was to help **PowerCo**, an energy provider, identify customers at risk of churn and recommend strategies to **boost retention and business growth**.

This project demonstrates how **data-driven insights** can transform customer relationships and improve revenue stability.
## 🎯 Business Objective The goal was to **reduce customer churn** by predicting which clients are most likely to leave and **developing actionable retention strategies** that align with PowerCo’s business goals. --- ## 
🧩 Key Tasks 1. **Data Exploration & Cleaning** – Examined customer usage, contract, and demographic data.
2. **Feature Engineering** – Created churn indicators and customer segments. 
3. **Predictive Modeling** – Trained and evaluated ML models using logistic regression and random forest.
4. **Business Insight Generation** – Interpreted results to recommend data-backed retention actions. --- ## 📈 Technologies Used | Category | Tools & Libraries | |-----------|-------------------| | Language | Python 🐍 | | Data Analysis | Pandas, NumPy | | Visualization | Matplotlib, Seaborn | | Notebook | JupyterLab | | Version Control | Git & GitHub | ---



## 💡 Business Insights - High consumption variability and short contract duration strongly correlate with churn. - Long-term contract incentives can reduce churn risk by **20–25%**. - Personalized retention offers should focus on **high-value customers** identified by the model. --- ## 🚀 Results - **Predicted churn probability** for 5,000+ customers. - Identified **top churn drivers** to guide PowerCo’s marketing and retention strategies. - Demonstrated how **AI-driven insights** can translate into **business growth and customer loyalty**. --- ## 🧾 Sample Code Snippet

python
# Feature importance visualization
import matplotlib.pyplot as plt
import pandas as pd

features = pd.Series(model.feature_importances_, index=X.columns).sort_values(ascending=False)
plt.figure(figsize=(8,5))
features.head(10).plot(kind='barh', color='skyblue')
plt.title('Top 10 Features Influencing Churn', fontsize=13, color='darkblue')
plt.xlabel('Importance', color='black')
plt.ylabel('Feature', color='black')
plt.show()
