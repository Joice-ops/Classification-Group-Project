# Customer Churn Prediction :office:

## Introduction :book:

This project involves building a predictive model to determine whether customers of a fictional telecommunications company will churn. Churn analysis is crucial for understanding why customers discontinue their services and what factors contribute to this decision. The dataset contains information about 7043 customers in California, including various demographic details, the company's services and products, customers' family members, Churn Score, and Customer Lifetime Value (CLTV) index.

## Project Structure :bookmark_tabs:

This project is organized as follows:
- Dataset: [Telco customer churn](https://community.ibm.com/community/user/businessanalytics/blogs/steven-macko/2019/07/11/telco-customer-churn-1113)
- [Classification_GroupProject](https://github.com/Joice-ops/Classification-Group-Project): The Jupyter Notebook containing the full analysis and modeling process. :link:
- [README.md](https://github.com/Joice-ops/Classification-Group-Project): This file, providing an overview of the project. :link:

## Analysis and Modeling :gear:

1. **Exploratory Data Analysis (EDA):** 
   - Examined the dataset to understand its structure.
   - Identified potential issues like missing data and incorrect data types.
   - Used visualizations to uncover trends and patterns.

2. **Data Cleaning and Preparation:** 
   - Cleaned the data to ensure it was suitable for modeling.
   - Identification of key features contributing to customer churn.

3. **Model Comparison:**
   - Compared three classification models: KNN Classifier, Logistic Regression, Random Forest.
   - Evaluated models using Confusion Matrix and Classification Report
   - Tuning Hyperparameters by GridSearchCV and selecting the best-performing model.

4. **Final Model Testing:**
   - Tested the final model by making predictions on new input data.
  
## Results :memo:

The final model Random Forest demonstrated strong performance metrics, with an accuracy score of 92%, indicating its effectiveness in identifying customers who are likely to churn. Here are the results of each model:

- KNN Classifier:
  + Accuracy Score: 0.89
  + Churn Precision Score: 0.79
  + Churn Recall Score: 0.79
    
- Logistic Regression:
  + Accuracy Score: 0.90
  + Churn Precision Score: 0.81
  + Churn Recall Score: 0.84
  
- Random Forest
  + Accuracy Score: 0.92
  + Churn Precision Score: 0.86
  + Churn Recall Score: 0.85
     
## Conclusion :page_facing_up:

By understanding the factors that contribute to churn, the company can take proactive measures to reduce churn rates, tailoring strategies to give more support to seniors, and sending out loyalty offers to customers who might leave, ultimately leading to increased customer retention and revenue.



