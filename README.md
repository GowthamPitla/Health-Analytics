## Healthcare Data Analysis

This project showcases a complete **Data Scientist workflow** applied to a real-world **healthcare dataset** containing 55,500 patient records. The analysis focuses on extracting meaningful insights from patient data, hospital operations, and billing information to support data-driven healthcare decisions.

---

### 🎯 Objective
The objective of this project is to:
- Analyze patient demographics and healthcare trends  
- Identify patterns in medical conditions and treatments  
- Evaluate hospital and doctor-wise billing performance  
- Generate actionable insights using data science techniques  

---

### 🔬 Data Science Methodology

#### 1. Data Understanding
- Explored dataset structure with 15 features  
- Identified key variables such as Age, Gender, Medical Condition, Billing Amount  
- Differentiated between categorical and numerical data  

---

#### 2. Data Cleaning & Feature Engineering
- Converted **Date of Admission** and **Discharge Date** into datetime format  
- Created a new feature: **Days Hospitalized** to measure patient stay duration  
- Removed irrelevant columns (Name, Room Number, Dates)  
- Validated dataset:
  - No missing values  
  - 534 duplicate records identified  

---

#### 3. Exploratory Data Analysis (EDA)
Performed in-depth analysis using statistical and visualization techniques:

- **Univariate Analysis**
  - Distribution of Age, Billing Amount, Hospital Stay  
- **Categorical Analysis**
  - Gender distribution  
  - Medical condition frequency  
  - Insurance provider usage  
- **Bivariate Analysis**
  - Gender vs Medical Condition  
  - Billing trends across hospitals and doctors  

---

#### 4. Data Visualization
Used visualization tools to uncover patterns:
- 📊 Histograms for numerical distributions  
- 📊 Bar and Pie charts for categorical insights  
- 🔥 Heatmap for correlation analysis  

---

#### 5. Statistical & Correlation Analysis
- Generated correlation matrix for key variables  
- Found **weak correlations**, indicating:
  - Healthcare outcomes depend on multiple complex factors  
  - No single variable strongly influences billing or hospitalization  

---

### 📊 Key Insights

- **Demographics**
  - Gender distribution is nearly equal  
  - Majority of patients fall in the **18–30 age group**  

- **Medical Trends**
  - Most common conditions: Arthritis, Diabetes, Hypertension  
  - Cancer is slightly more prevalent among females  

- **Billing Analysis**
  - Average billing amount: ~25,539  
  - Top hospitals generate over **1M in total billing**  
  - Certain doctors contribute significantly to revenue  

- **Hospital Stay**
  - Slight increase in hospital stay with age  
  - No strong relationship between billing and hospitalization duration  

---

### 💡 Conclusion
This project highlights how **data science techniques** can be used to:
- Understand healthcare trends  
- Identify inefficiencies in hospital billing  
- Support better decision-making in the healthcare sector  

The weak correlations observed suggest that **healthcare systems are highly complex**, requiring advanced modeling techniques for deeper insights.

---

### 🚀 Future Scope
- Build **Machine Learning models** for:
  - Cost prediction  
  - Disease risk classification  
- Develop interactive dashboards using **Power BI / Tableau**  
- Implement predictive analytics for hospital resource planning  

---

### 👨‍💻 Author
**Gowtham Pitla**  
B.Tech – Artificial Intelligence & Data Science  
