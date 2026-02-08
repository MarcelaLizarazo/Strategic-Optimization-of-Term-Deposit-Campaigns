# Strategic-Optimization-of-Term-Deposit-Campaigns


## 📖 Overview
This project analyzes direct marketing campaigns from a Portuguese bank to predict which clients are likely to subscribe to a term deposit.

The dataset is highly imbalanced (low subscription rate), making this a realistic business problem where accuracy alone is not enough.

The project combines predictive modeling, client segmentation, and dashboarding to support smarter campaign decisions.

---

## 🎯 Business Objective
- Predict likelihood of term deposit subscription  
- Segment clients based on behavior  
- Help marketing teams prioritize high-value leads  
- Reduce wasted outreach on low-probability clients  

---

## 🧠 Methodology

### Predictive Model
- Random Forest classifier  
- SMOTE to handle class imbalance  
- Threshold tuning (0.35) to improve sensitivity  
- Evaluated using Precision, Recall, and F1-score  

### Client Segmentation
- K-Means clustering  
- Segments built on demographic and campaign attributes  
- Identified high and low conversion groups  

---

## 📊 Dashboard
A Power BI dashboard was built to:

- Explore historical campaign performance  
- Filter by client segments  
- Highlight high-probability leads  
- Support targeting decisions  

Includes:
- Training View (behavior analysis)  
- Prediction View (lead prioritization)

---

## 💡 Key Insights
- Only ~11% of clients subscribed, highlighting imbalance  
- Certain clusters show significantly higher conversion rates  
- Over-contacted segments show low response and potential fatigue  
- Targeted outreach can improve efficiency  

---

## 🛠 Tools & Technologies
- Python (Pandas, Scikit-learn)  
- Power BI  
- Jupyter Notebook
  
---

## 📌 Dataset Source
UCI Machine Learning Repository — Bank Marketing Dataset
