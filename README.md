# Feature Analysis for Alzheimer’s Risk – NeuroScope

A machine learning–driven health analytics project to identify key predictors of Alzheimer’s Disease (AD) using clinical and cognitive features. The project explores feature importance, model interpretability, and fairness across demographic subgroups using models like Logistic Regression, Random Forest, and XGBoost.

This repository contains the **NeuroScope** project, developed as part of a graduate-level Machine Learning course. It focuses on identifying risk factors for Alzheimer’s through explainable and fair ML pipelines, backed by SHAP and LIME interpretability techniques and subgroup-based fairness evaluation.

---

## 📜 **Project Overview**

The project analyzes patient-level tabular data to detect early indicators of Alzheimer’s Disease. By applying multiple classification algorithms and interpretability techniques, we aim to highlight the most significant medical and cognitive features contributing to the disease onset and ensure model fairness across gender, age, and ethnicity.

### **Objectives**
1. Train and evaluate ML models (Logistic Regression, Random Forest, XGBoost) on clinical AD data.
2. Identify influential features using SHAP and LIME explainability tools.
3. Analyze model fairness across gender, age, and ethnicity to detect potential biases.

---

## 🚀 **Key Highlights**

### **Technical Approach**
1. **Data Preprocessing & EDA**:
   - Handled missing values, normalized features, and encoded categorical variables.
   - Performed exploratory data analysis with correlation heatmaps and scatter plots.

2. **Model Training**:
   - Built Logistic Regression, Random Forest, and XGBoost classifiers.
   - Evaluated models using accuracy, ROC-AUC, and confusion matrices.

3. **Model Explainability**:
   - Used **SHAP** (TreeExplainer) to visualize feature contributions and global importance.
   - Employed **LIME** for instance-level explanations to understand model behavior on individual samples.

4. **Fairness Analysis**:
   - Tested model outcomes for fairness across **gender**, **age groups**, and **ethnicity** using XGBoost.
   - Performed subgroup-based evaluation using accuracy and confusion matrices.

---

## 📊 **Key Findings**

1. **Top Features**:
   - Key features included ADAS13 (cognitive score), CDRSB, and MMSE, confirming medical literature.

2. **Model Comparison**:
   - XGBoost consistently outperformed other models with the highest ROC-AUC.
   - Logistic Regression offered better interpretability but lower predictive performance.

3. **Fairness Observations**:
   - Fairness disparities were observed across age groups, with older patients seeing slightly lower accuracy.
   - Model explanations differed subtly across ethnic groups, underlining the importance of inclusive training.

---

## 🌟 **Impact and Implications**

This project offers:
- **Clinical Insight**: Early identification of cognitive metrics that contribute most to Alzheimer’s risk.
- **Responsible AI**: Demonstrates how ML pipelines can incorporate fairness checks to avoid biased healthcare outcomes.
- **Educational Value**: Serves as a reproducible example of explainable AI in healthcare analytics.

---

## 🛠️ **Technologies Used**

- **Programming Language**: Python  
- **Libraries & Tools**:  
  - Scikit-learn, XGBoost, LIME, SHAP  
  - Pandas, NumPy, Matplotlib, Seaborn  
  - Jupyter Notebooks for step-by-step modeling and visualizations

---

## 💡 **Future Directions**
1.	**Larger Dataset**:
	Use more comprehensive clinical datasets like ADNI or OASIS for broader generalization.
2.	**Time-Series Modeling**:
	Study patient progression over time using LSTM or survival analysis techniques.
3.	**Model Optimization**:
	Perform hyperparameter tuning and ensembling for improved results.
4.	**Broader Fairness Metrics**:
	Explore metrics like Equal Opportunity Difference and Disparate Impact Ratio.

---

## 🔗 **Portfolio & Contact**

This project is part of my Data Science Portfolio, demonstrating my ability to blend machine learning with responsible AI principles. For inquiries or collaborations, feel free to connect:

- Email: shayan.raja123@gmail.com  
- LinkedIn: [https://www.linkedin.com/in/shayanraja](https://www.linkedin.com/in/shayanraja)
