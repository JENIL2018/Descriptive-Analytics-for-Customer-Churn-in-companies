# Descriptive-Analytics-for-Customer-Churn-in-companies

## 📊 Overview

This project leverages **Descriptive Analytics and Exploratory Data Analysis (EDA)** to uncover insights into **customer churn** patterns in SaaS-based and similar industries. We analyzed multiple datasets spanning retail, telecom, energy, and e-commerce to detect at-risk users and build data-informed customer retention strategies.

---


## 📌 Problem Statement

SaaS companies suffer significant losses due to customer churn. Retaining customers is more cost-effective than acquiring new ones. This project aims to analyze behavioral, demographic, and transactional data to identify early indicators of churn and provide strategies for retention.

---

## 🔍 Key Focus Areas

1. **Usage Pattern Analysis**: Track engagement trends to detect churn risk.
2. **Price Sensitivity Across Segments**: Explore how pricing affects customer loyalty.
3. **Customer Segmentation**: Predict churn probability based on customer demographics and behavior.

---

## 📁 Datasets Used

1. **Retail Sales and Behavior**
2. **E-commerce Platform Usage**
3. **PowerCO Energy Churn**
4. **Telco Customer Churn**
5. **Cell2Cell Telecom Dataset**

All datasets were sourced from [Kaggle](https://www.kaggle.com/).

---

## 🧹 Data Preparation

- Cleaned and converted data types (e.g., strings to numeric).
- Handled missing values using median/mode imputation.
- Feature engineered attributes like `tenure_category`, `frequency_score`, and `total_forecast_price`.
- Applied one-hot encoding to categorical variables.

---

## 📈 Exploratory Data Analysis (EDA)

Key insights derived from EDA:

- Low **usage frequency** strongly correlates with higher churn.
- **Mobile app usage** is linked with better retention compared to desktop usage.
- Customers with **enabled push notifications** churn significantly less.
- Higher **peak energy prices** and **monthly charges** are associated with increased churn.
- **Price-sensitive segments**, especially younger and online-only shoppers, show higher churn.
- Features like **wishlist usage**, **engagement recency**, and **discount responsiveness** serve as useful churn indicators.

---

## ⚠️ Limitations

- Limited emotional/sentiment data (e.g., no feedback/surveys).
- No external competitor pricing or economic conditions included.
- Analysis focused on historical data — not real-time or streaming.
- May not generalize across all SaaS providers or regions.

---

## ✅ Recommendations

- Encourage multi-platform consistency.
- Focus retention efforts on new users (first 12 months).
- Use personalized and proactive communication.
- Offer flexible pricing/payment options.
- Enhance customer support responsiveness.

---

## 🤖 ChatGPT Usage

ChatGPT was utilized to:
- Identify key influencing variables.
- Suggest visualizations and interpret plots.
- Troubleshoot data presentation issues.
- Generate hypotheses and business questions.
- Assist in structuring insights and recommendations.

---

## 📚 References

- Kaggle Datasets (Retail, E-Commerce, PowerCO, Telco, Cell2Cell)  


---

## 📌 Conclusion

This analysis demonstrates that EDA can provide deep insights into customer behavior and churn drivers. With the right data and targeted strategies, SaaS companies can enhance customer satisfaction, reduce churn, and drive long-term growth.

---

> *For detailed plots, visuals, and code, refer to the full project notebook/report.*
