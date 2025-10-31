# Loan-Prediction-Project
A machine learning project comparing Logistic Regression, Discriminant Analysis, and Neural Networks to predict loan approvals using financial datasets. Achieved up to 95.7% validation accuracy, showcasing data-driven, fair, and efficient decision-making in lending.

# 🧠 Optimizing Loan Decision-Making: A Comparative Analysis of Predictive Models

### 📌 Overview
This project explores how **machine learning** can improve the **loan approval decision-making process** by replacing subjective, time-consuming evaluations with **data-driven predictive modeling**.

By analyzing financial datasets and comparing **Logistic Regression, Discriminant Analysis,** and **Neural Networks**, this project identifies the most effective model for accurate loan approval predictions.  
The final results demonstrate how neural networks can significantly enhance both **accuracy and fairness** in lending decisions.

---

### 👩‍💻 Contributor
**Sheetal Patangay** 
*School of Business Administration, The Pennsylvania State University*  
Course: **BUS 510 — Business Analytics and Decision Modeling**  
Instructor: *Dr. Dinesh R. Pai*

---

### 📊 Dataset Overview
- **Source:** Kaggle (L&T Financial Services Loan Dataset)
- **Records:** 4,269 financial entries
- **Features:** 13 columns including `income_annum`, `loan_amount`, `loan_term`, `cibil_score`, and asset values.
- **Target:** `loan_status` → *Approved (1)* or *Not Approved (0)*  
- **Problem Type:** Binary classification

---

### ⚙️ Data Preprocessing
- Dropped irrelevant column: `loan_id`
- Encoded categorical variables:
  - `education`: Graduated → 1 | Not Graduated → 0  
  - `self_employed`: Yes → 1 | No → 0  
  - `loan_status`: Approved → 1 | Not Approved → 0  
- Performed data stratification (70% training / 30% testing split)
- Verified dataset completeness — no missing or NaN values

---

### 📈 Models Implemented
1. **Logistic Regression**  
   - Captures the probability of loan approval.  
   - Achieved **91.6% training accuracy** and **91.2% validation accuracy**.  
   - Model effectively predicts approval likelihood based on financial variables.

2. **Discriminant Analysis**  
   - Classifies observations into “Approved” or “Rejected” based on linear discriminants.  
   - Achieved **91.7% training accuracy** and **91.8% validation accuracy**.  
   - Strong interpretability for categorical decision-making.

3. **Neural Network Analysis**  
   - Multi-layer architecture designed to recognize complex relationships.  
   - Achieved **99.5% training accuracy** and **95.75% validation accuracy**.  
   - Outperformed other models in predictive precision and recall.

---

### 🧩 Model Comparison

| Model | Training Accuracy | Validation Accuracy |
|:------|:------------------:|:--------------------:|
| Logistic Regression | 91.6% | 91.2% |
| Discriminant Analysis | 91.7% | 91.8% |
| Neural Network | **99.5%** | **95.75%** |

✅ **Neural Network** emerged as the most accurate and robust model for loan approval prediction.

---

### 🔍 Key Findings & Insights
1. **CIBIL Score Dominance:** The credit score proved to be the most critical predictor of loan approval.  
2. **Income–Loan Balance:** The ratio of annual income to loan amount significantly influences approval likelihood.  
3. **Luxury Assets:** Presence of luxury assets contributed more positively than expected.  
4. **Self-Employment Nuances:** Stability of self-employment mattered more than status alone.  
5. **Education Factor:** Graduates showed consistently higher approval rates.  
6. **Collateral Importance:** Higher residential and commercial asset values strongly correlated with approval.

---

### 🧾 Hypothesis Testing
- **Null (H₀):** No difference in mean values of numeric features between approved and rejected loans.  
- **Alternative (H₁):** There is a significant difference.  
✅ Result: Rejected the null hypothesis — strong statistical evidence that feature means differ between the two loan status classes.

---

### 💡 Lessons Learned
- Neural networks can transform financial decision-making by learning from patterns traditional models might miss.  
- Data preprocessing and feature encoding have a direct impact on model performance.  
- Model interpretability remains essential for trust and transparency in lending.  
- Combining technical models with domain understanding ensures more **equitable and efficient** loan approvals.

---

### 🚀 Future Improvements
- Integrate **real-time financial data** for live prediction dashboards.  
- Explore **Deep Learning** architectures (e.g., LSTM, CNN).  
- Add **Explainable AI (XAI)** components for interpretability.  
- Deploy a **Flask or Streamlit web app** for user interaction.

---

### 🧮 Tools & Technologies
| Category | Tools Used |
|:----------|:------------|
| Data Processing | Excel, Python, IBM SPSS |
| Modeling | Neural Networks, Logistic Regression, Discriminant Analysis |
| Visualization | Tableau, Matplotlib |
| Source | Kaggle |
| Platform | Jupyter Notebook / Excel Neural Network Add-In |

---

### 🏁 Conclusion
This project demonstrates how **machine learning can optimize loan approval workflows**, reduce manual bias, and improve financial inclusion.  
By combining analytical precision with ethical responsibility, predictive models like these pave the way for **data-driven, transparent, and scalable** decision-making in finance.

---

### 🔗 Repository Structure
