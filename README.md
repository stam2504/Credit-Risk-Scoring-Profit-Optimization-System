# 📈 Credit Risk Scoring & Profit Optimization System

## 🎯 Executive Summary
This project bridges the gap between **Machine Learning** and **Banking Strategy**. Moving beyond simple default prediction, I developed a decision-making framework that maximizes loan portfolio profitability by integrating core **Basel III/IV** concepts. By aligning statistical accuracy with financial outcomes, the system identifies the optimal balance between risk appetite and revenue generation.

---

## 🚀 Key Implementation Stages

* **Risk Engine (PD Modeling):** Developed a Logistic Regression model emphasizing interpretability and stability.
* **Standardized Credit Scorecard:** Converted Probabilities of Default (PD) into a standard **300-850 range** using the **PDO (Points to Double the Odds)** methodology.
* **Profit Optimization:** Identified an **Optimal Threshold of 506**, maximizing expected profit at **41,000 CHF** by balancing interest gains against default losses.
* **Stability Monitoring:** Achieved a **Population Stability Index (PSI) of 0.0101**, indicating an extremely stable model ready for production.
* **Risk Metrics (EL Framework):** Integrated **LGD (Loss Given Default)** and **EAD (Exposure at Default)** to calculate the **Expected Loss (EL)** per applicant.

---

## 📊 Dashboard Preview
![Dashboard](Credit_Risk_Scoring_Dashboard.png)
*Interactive Power BI dashboard used for "What-If" scenario analysis and portfolio risk monitoring.*

---

## 🛠️ Technical Stack
* [cite_start]**Languages:** Python (Pandas, NumPy, Matplotlib, Seaborn) [cite: 7, 13]
* [cite_start]**Machine Learning:** Scikit-Learn (Logistic Regression, Scaling, Learning Curves) [cite: 13]
* [cite_start]**Business Intelligence:** Power BI (DAX, Interactive Visualization) [cite: 7, 8, 13]
* [cite_start]**Database:** SQL for data extraction and preparation [cite: 7, 13]

---

## 💡 Business Value & Insights
* **Dynamic Strategy:** Instead of static rules, the model allows for dynamic limit setting based on the **Net Economic Value** of each loan.
* **Regulatory Alignment:** The methodology follows banking standards for credit risk reporting, making it suitable for Fintech and traditional banking environments.
* **Explainability:** Utilizing feature importance and scoring mechanics to provide transparent "Reason Codes" for loan approvals or rejections.

