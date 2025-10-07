#  Data Science Job Salary Prediction using Machine Learning

##  Project Overview
This project aims to predict **Data Science job salaries** using **Machine Learning** techniques.  
By analyzing various job-related features such as experience level, employment type, and company size,  
this model helps estimate salary levels in the Data Science industry.

---

##  Dataset
- **Source:** [Kaggle](https://www.kaggle.com/)
- The dataset contains details about job titles, experience levels, employment types, company locations, and corresponding salaries.

---

##  Machine Learning Models Used
| Model | R² Score | RMSE |
|--------|-----------|-------|
| Decision Tree Regressor | 0.30 | 54,498 |
| Random Forest Regressor | 0.34 | 52,961 |

The **Random Forest Regressor** performed slightly better than the Decision Tree model,  
indicating that ensemble methods improved the model’s predictive accuracy.

---

##  Technologies and Libraries
- **Language:** Python  
- **Libraries:**  
  - pandas  
  - numpy  
  - matplotlib  
  - seaborn  
  - scikit-learn  

---

##  Workflow
1. **Data Loading & Exploration**  
   - Imported and examined the dataset  
   - Checked for missing values and data distribution  

2. **Data Cleaning & Feature Engineering**  
   - Handled null values  
   - Encoded categorical variables  
   - Performed feature scaling and selection  

3. **Model Building**  
   - Trained Decision Tree and Random Forest models  
   - Tuned hyperparameters for better accuracy  

4. **Model Evaluation**  
   - Compared models using R² Score and RMSE metrics  

5. **Visualization**  
   - Created correlation heatmaps, bar charts, and feature importance plots  

---

##  Results
- Random Forest outperformed Decision Tree by reducing error and improving prediction stability.  
- The model successfully demonstrated how machine learning can be used to estimate real-world salaries in the data science domain.

---

##  Future Improvements
- Implement **Deep Learning** techniques to enhance feature representation.  
- Collect more diverse job market data to improve model generalization.  
- Deploy the model as a web app for real-time salary prediction.

---

##  Author
**NirmalanSK**  
 [GitHub Profile](https://github.com/NirmalanSK)

---

## 🏁 Conclusion
This project demonstrates how machine learning can be applied to predict job salaries efficiently.  
It highlights the importance of data preprocessing, feature selection, and model evaluation in real-world data science workflows.
# DataScience-Job-Salary-Prediction-using-ML
