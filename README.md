# ✈️ Optimizing Air Travel  
## A Data-Driven Approach to Flight Delay Analysis and Prediction

---

## 📌 Project Overview

Flight delays are a major operational challenge in the aviation industry. They lead to passenger inconvenience, financial losses for airlines, and cascading disruptions across airport operations.

This project uses **data analytics and machine learning** to analyze historical flight data, identify key contributors to delays, and build predictive models to help airlines **proactively minimize disruptions** and improve operational efficiency.

---

## 🎯 Objectives

- Analyze historical flight delay patterns  
- Identify key factors contributing to delays  
- Predict:
  - Whether a flight will be delayed (**Classification**)
  - Delay duration in minutes (**Regression**)
- Apply **Explainable AI (SHAP)** for model interpretability  
- Provide **actionable operational recommendations**

---

## 🔁 Project Workflow

1. Data Loading and Cleaning  
2. Feature Selection  
3. Exploratory Data Analysis (EDA)  
4. Model Development  
   - Classification  
   - Regression  
5. Hyperparameter Tuning  
6. Model Evaluation  
7. Model Interpretability (SHAP)  
8. Operational Insights & Recommendations  

---

## 📊 Exploratory Data Analysis (EDA)

Key insights from the data:

- Delay distribution is **positively skewed**
  - Most delays are less than **30 minutes**
  - Few flights experience very large delays
- Certain **carriers and airports** show higher delay variability
- Congestion plays a significant role in increasing delay probability

<img width="1811" height="1265" alt="image" src="https://github.com/user-attachments/assets/196b1eeb-1373-43d6-876c-ff7319d6b966" />

### Carrier & Airport Variability
- Certain **carriers and airports** exhibit higher delay variability
- Congestion and operational inefficiencies are key contributors

<img width="520" height="420" alt="image" src="https://github.com/user-attachments/assets/b0c6b4dc-006f-4e8d-afcf-0559cac82d19" />


---

## 🤖 Model Development

### 🔹 Classification (Delayed: Yes / No)

**Models Used**
- Logistic Regression  
- Gradient Boosting Classifier  

**Hyperparameter tuning:** GridSearchCV  

**Performance Metrics**
- Accuracy: **87%**
- Precision: **86%**
- F1-Score: **87%**
- AUC-ROC: **0.91**

**Classification Model Performance**
<img width="681" height="510" alt="image" src="https://github.com/user-attachments/assets/58c19c24-9c7f-411f-a720-d15a61f0c3aa" />
<img width="748" height="549" alt="image" src="https://github.com/user-attachments/assets/6898046f-ed6f-4a00-8c65-d3965df4cb02" />


➡️ Strong ability to distinguish delayed and non-delayed flights.

---

### 🔹 Regression (Delay in Minutes)

**Model Used**
- Gradient Boosted Regressor  

**Performance Metrics**
- RMSE: **14 minutes**
- MAE: **10 minutes**
- R² Score: **79%**

<img width="650" height="336" alt="image" src="https://github.com/user-attachments/assets/254bec38-eabc-4ee2-9394-7ec83564e5ff" />

**Model Comparison: MAE and RMSE**
<img width="650" height="319" alt="image" src="https://github.com/user-attachments/assets/e1e58205-be7e-47d2-ab94-b25a55a4979e" />

**Model Comparison: R2 Score**
<img width="614" height="319" alt="image" src="https://github.com/user-attachments/assets/02dbba84-e2ba-47db-9e62-ffd54fbffc21" />

➡️ Model explains most of the variance in delay duration.

---

## 🧩 Explainable AI (SHAP & OAI Score)

- **SHAP** was used to interpret black-box models and identify influential features  
- **Operational Actionability Index (OAI)** emphasizes controllable delay factors  
- Helps operations teams focus on changes with maximum real-world impact

**SHAP Value** 
<img width="837" height="476" alt="image" src="https://github.com/user-attachments/assets/726f94af-bbd5-4587-8b60-629c952515fc" />

**AVG OAI**
<img width="837" height="211" alt="image" src="https://github.com/user-attachments/assets/3b7019ed-29bb-4283-91c1-496627b608a4" />


---

## 🚀 Actionable Recommendations

Based on analytical and ML insights:

1. **Schedule Adjustment**  
   - Spread departure times to reduce congestion  
2. **Proactive Communication**  
   - Early alerts for high-risk flights  
3. **Targeted Improvements**  
   - Audit consistently underperforming carriers and airports  
4. **Efficient Resource Allocation**  
   - Deploy backup crews and resources where delay risk is high  

---

## ✅ Conclusion

This project demonstrates how a **data-driven and explainable ML pipeline** can:

- Reduce flight delays  
- Cut operational costs  
- Improve passenger satisfaction  
- Enable proactive decision-making in airline operations  

---

## 📁 Repository Structure
<pre>
Optimizing-Air-Travel/
├── Optimizing Air Travel.ipynb
├── Otimizing Air Travels_(Analytics).pptx
└── README.md
</pre>
                          


---

## 🛠️ Technologies Used

- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  
- SHAP  
- Jupyter Notebook  

---







