# **AI for HumanForYou - Employee Turnover Analysis**  

## **Project Overview**  
This project aims to analyze employee turnover at **HumanForYou**, a pharmaceutical company in India. The company experiences a **15% annual turnover rate**, affecting project timelines, increasing HR workload, and causing inefficiencies in employee training.  

As data analysts, our goal is to:  
✔ Identify key factors influencing employee attrition.  
✔ Develop predictive models to assess turnover risks.  
✔ Provide data-driven recommendations to improve employee retention.  

## **Dataset Information**  
The analysis is based on **multiple anonymized datasets** provided by the HR department, including:  

- **`general_data.csv`** – Employee demographics, salary, and job details.  
- **`manager_survey_data.csv`** – Performance and job involvement ratings from managers.  
- **`employee_survey_data.csv`** – Employee satisfaction survey responses.  
- **`in_out_time.zip`** – Employee work hours based on check-in/check-out data.  

Each dataset includes an **EmployeeID**, allowing data integration across files.  

## **Project Objectives**  
1. **Data Cleaning & Preparation:**  
   - Handle missing values, normalize categorical data, and merge datasets.  
2. **Exploratory Data Analysis (EDA):**  
   - Visualize turnover patterns across various features (e.g., salary, job level, travel frequency).  
3. **Machine Learning Models:**  
   - Train predictive models (Logistic Regression, Decision Trees, Random Forest, etc.) to identify attrition risk factors.  
4. **Ethical Considerations:**  
   - Ensure fairness, transparency, and responsible AI usage.  

## **Installation & Requirements**  
To run this project, install the required Python libraries:  
```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter
```  

### **How to Run the Notebook**  
1. Clone the repository:  
   ```bash
   git clone https://github.com/equisdel/INDIAI.git
   cd INDIAI
   ```  
2. Open Jupyter Notebook:  
   ```bash
   jupyter notebook
   ```  
3. Open and run `final.ipynb` step by step.  

## **Analysis & Findings**  
📌 **Key Factors Influencing Turnover:**  
- Employees with **low job satisfaction** and **poor work-life balance** were more likely to leave.  
- **Frequent business travel** and **long commute distances** contributed to higher attrition.  
- **Salary and job level disparities** affected retention rates.  

📌 **Best Performing Model:**  
- The **Random Forest model** achieved the highest accuracy in predicting employee attrition.  
- Feature importance analysis highlighted **work-life balance, job satisfaction, and salary growth** as major predictors.  

## **Ethical Considerations**  
We followed ethical AI guidelines based on the **European Commission’s 7 AI ethics principles**, including:  
- **Fairness & Non-Discrimination** – Ensuring no bias in model predictions.  
- **Transparency** – Clear explanations of model decisions.  
- **Privacy & Data Security** – Handling employee data responsibly.  

## **Final Recommendations**  
✔ **Improve work-life balance** by offering flexible work arrangements.  
✔ **Enhance job satisfaction** with better career growth opportunities.  
✔ **Optimize salary structures** to retain high-performing employees.  
✔ **Reduce travel strain** by offering remote/hybrid work options.  

## **Conclusion**  
This project successfully identifies turnover factors and proposes solutions to **improve employee retention** at HumanForYou. By implementing data-driven HR strategies, the company can minimize attrition and enhance overall workforce stability.  

## **Credits**
This project was conducted as part of a school assignment by Team INDIAI:

**FERRERI Delfina**
**TARDIVEL Shiva**
**VESCHAMBRE Mathis**
**THONTIA Manav**
