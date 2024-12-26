# Student Dropout and Academic Success Prediction  

## Project Overview  
Education serves as a transformative tool for personal growth and societal advancement, with higher education offering life-changing opportunities. However, increasing dropout rates in higher education institutions present a significant challenge. This project seeks to uncover the key predictors influencing student dropout and academic success, aiming to identify at-risk students early and support effective interventions.  

By analyzing a rich dataset containing demographic, socioeconomic, and academic performance variables, this project addresses pressing questions about student retention and success through data-driven insights.  



## Research Objectives  

### **Research Question:**  
What are the main demographic, socioeconomic, and academic predictors that influence student dropout rates and academic success in higher education?  

### **Hypotheses:**  
- **Primary Hypothesis:** Socioeconomic and demographic factors, such as family background and economic conditions, significantly impact dropout rates.  
- **Secondary Hypothesis:** Academic performance metrics, such as grades and attendance, are reliable indicators of academic success.  



## Methodology  

### 1. **Exploratory Data Analysis (EDA):**  
- Visualized trends in dropout, retention, and success rates.  
- Summarized dataset attributes to identify key patterns.  

### 2. **Data Preprocessing:**  
- Addressed missing values, outliers, and inconsistencies in demographic, socioeconomic, and academic data.  

### 3. **Feature Engineering:**  
- Applied Principal Component Analysis (PCA) for dimensionality reduction and selection of critical predictors.  

### 4. **Predictive Modeling:**  
Developed machine learning models to classify and predict student outcomes:  
- **Logistic Regression**  
- **Support Vector Machines (SVM)**  
- **Random Forest**  



## Dataset Details  

### **Source:**  
The dataset originates from a higher education institution and is part of the SATDAP program, funded by Portugal’s Public Administration.  

### **Key Features:**  
- **Demographic Data:** Includes age, gender, marital status, and family background.  
- **Socioeconomic Variables:** Covers parental education levels, employment, and income brackets.  
- **Academic Metrics:** Tracks grades, attendance, and performance trends across semesters.  

### **Target Variable:**  
- **Student Outcome:** Categorized as:  
  - Dropout  
  - Enrolled  
  - Graduate  

The dataset allows a multifaceted exploration of dropout risks and academic performance outcomes.  



## Project Contributions  
- Early identification of at-risk students through predictive models.  
- Insightful analysis of factors influencing academic retention and success.  
- Scalable machine learning pipeline adaptable to similar educational datasets.  



## Technologies Used  
- **Languages:** Python  
- **Libraries & Tools:**  
  - Data Exploration: `Pandas`, `Seaborn`, `Matplotlib`  
  - Machine Learning: `Scikit-learn`, `XGBoost`  
  - Preprocessing: `NumPy`  
  - Dimensionality Reduction: `PCA`  


## How to Run the Project  
1. Clone the repository.  
2. Install dependencies listed in `requirements.txt`.  
3. Run the provided Jupyter notebooks for EDA and modeling.  
