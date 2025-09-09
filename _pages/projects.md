---
permalink: /projects/  # 必须与导航 url 完全匹配
title: "Key Projects"
author_profile: true
layout: single
---

## Project 1: Bank Customer Product Subscription Prediction  
**Role**: Independent Project Lead | **Duration**: Jun. 2024 – Jul. 2024  
**Goal**: Predict whether bank customers will subscribe to financial products (e.g., fixed deposits)，providing data support for targeted marketing.  


### 1. Data Preprocessing  
- **Data Source**: Public bank customer dataset (2 files: `train.csv` (45k rows)、`test.csv` (15k rows))，containing 17 features (age, income, education, loan status, etc.);  
- **Cleaning Steps**:  
  - Handled missing values: Imputed numerical features (e.g., balance) with mean，categorical features (e.g., job) with mode;  
  - Removed outliers: Used IQR method to filter extreme values in "age" and "balance" (reduced noise by 8%);  
  - Encoding: Applied LabelEncoder to categorical features (e.g., "marital" → 0=single, 1=married) for model compatibility.  


### 2. Exploratory Data Analysis (EDA)  
- **Key Insights** (via Matplotlib/Seaborn visualizations):  
  - Middle-aged customers (35–55 years old) had a 2x higher subscription rate than young/elderly groups;  
  - Customers with no housing loan and high monthly balance (>¥50k) were 3x more likely to subscribe;  
  - Correlation heatmap showed "monthly balance" (r=0.72) and "duration of last contact" (r=0.68) were the top 2 predictive features.  


### 3. Model Development & Optimization  
- **Models Tested** (via scikit-learn):  
  | Model               | Baseline Accuracy | Optimized Accuracy | Training Time |  
  |---------------------|-------------------|---------------------|---------------|  
  | Logistic Regression | 78%               | 82%                 | 12s           |  
  | Random Forest       | 83%               | 86%                 | 45s           |  
  | XGBoost             | 85%               | 89%                 | 38s           |  
  | LightGBM            | 84%               | 88%                 | 32s           |  
- **Optimization Strategy**:  
  - Used 5-fold cross-validation (KFold) to avoid overfitting;  
  - Tuned XGBoost parameters via grid search: `n_estimators=200`, `learning_rate=0.05`, `max_depth=6` (key to accuracy improvement).  


### 4. Project Outcome  
- The final XGBoost model achieved **89% accuracy**、87% precision、85% recall on the test set;  
- Proposed targeted marketing strategies:  
  - Prioritize middle-aged customers (35–55) with high monthly balance (>¥50k) and no housing loan;  
  - Launch personalized product recommendations via bank APP notifications (estimated to increase subscription rate by 25%).  


## Project 2: RAG-Based Intelligent Agent (Xiaoduo Tech Internship)  
**Role**: Core Developer | **Duration**: Jul. 2024 – Sep. 2024  
**Tech Stack**: Python, Elasticsearch, Streamlit, LLaMA-2-7B  
**Key Deliverables**:  
- Built a RAG knowledge base with 10k+ product documents (e.g., user manuals, FAQs);  
- Developed a query routing system that classified user questions into 4 types (accuracy 92%);  
- Created a Streamlit demo with 500+ test interactions (average response time <2s).  


### Download Project Materials  
- [Project 1 Code (GitHub)](https://github.com/kiko022/bank-customer-prediction) – View data preprocessing/modeling scripts  
- [6-Page Portfolio (PDF)](/files/portfolio.pdf) – See visual charts of project results  
- [Full CV (PDF)](/files/CV.pdf) – Get detailed project documentation
