
# Employee Attrition Analysis

This project explores the reasons behind employee attrition and predicts which employees might leave a company in the future. The insights from this analysis can help organizations take proactive measures to enhance employee satisfaction and retention.

## Goal

To analyze employee data, understand attrition patterns, and build predictive models to identify employees at risk of leaving.

## Steps Undertaken

1. *Understanding the Data*  
   - Worked with a dataset containing employee attributes like age, job role, salary, tenure, and attrition status.  
   - Addressed missing data by imputing averages to ensure a complete analysis.

2. *Initial Observations*  
   - Visualized trends to identify factors such as age, income levels, and satisfaction rates influencing attrition.  
   - Discovered that younger employees or those with lower satisfaction were more likely to leave.

3. *Building Prediction Models*  
   - *First Approach:*  
     - Implemented Logistic Regression and Random Forest models.  
     - Random Forest achieved an accuracy of 97%, outperforming Logistic Regression.  
   - *Second Approach:*  
     - Refined data preparation and used advanced techniques like the XGBoost model.  
     - Achieved improved accuracy of 99%.

4. *Key Findings*  
   - Identified critical factors influencing attrition, including:  
     - Job satisfaction  
     - Age  
     - Marital status  
     - Years at the company  
   - Highlighted that employees with low satisfaction or shorter tenures are more likely to leave.

5. *Impact*  
   - Provided actionable insights to help organizations focus on improving job satisfaction and work-life balance.  
   - Helped reduce costs associated with employee turnover and foster a stable workforce.

## Technologies Used

- *Programming Language:* Python  
- *Models:* Logistic Regression, Random Forest, XGBoost  
- *Libraries:* Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, XGBoost  

## Key Takeaways

This project showcases skills in data analysis, predictive modeling, and actionable insight generation. By identifying patterns in employee attrition, the analysis can help organizations improve retention strategies effectively.
"""

file_path = "/mnt/data/README.md"
with open(file_path, "w") as f:
    f.write(readme_content)

file_path
