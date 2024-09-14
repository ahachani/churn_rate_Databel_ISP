### Project Title
**Customer Churn Prediction Analysis for Databel**

**Author**
Adel Hachani

#### Executive Summary
This project focuses on analyzing and predicting customer churn for **Databel**, an internet service provider. By applying machine learning techniques to customer data, we identified key factors driving churn and built predictive models to help Databel reduce churn and retain more customers. The results provide actionable insights to improve customer retention and guide Databel's efforts to minimize churn rates.

#### Rationale
Customer churn is a critical issue for any subscription-based business, as losing customers directly impacts revenue. By understanding why customers leave and predicting which customers are at risk, Databel can implement targeted strategies to reduce churn and improve customer satisfaction, which ultimately drives long-term business success.

#### Research Question
What are the primary factors driving customer churn at Databel, and how can we predict which customers are most likely to churn?

#### Data Sources
The data used for this project contains information on over 6,000 Databel customers, including:
- **Customer Usage Metrics**: Local and international call minutes, customer service interactions, data plan usage, and contract type.
- **Customer Demographics**: Age, gender, senior status, and group size.
- **Financial Data**: Monthly charges, total charges, and payment methods.

The dataset is from [Kaggle](https://www.kaggle.com/datasets/yichienchong/databel-telecom-customer-churn-dataset/data).

#### Methodology
The project followed the **CRISP-DM** framework:
1. **Business Understanding**: Identify key factors contributing to churn and develop models to predict high-risk customers.
2. **Data Preparation**: Clean, preprocess, and encode the dataset to make it suitable for machine learning.
3. **Modeling**: Use machine learning algorithms including Logistic Regression, K-Nearest Neighbors (KNN), Support Vector Classifier (SVC), Decision Tree, Random Forest, and Gradient Boosting to build churn prediction models.
4. **Evaluation**: Evaluate models based on accuracy, precision, recall, F1-score, and ROC-AUC scores.
5. **Interpretation**: Analyze the feature importance and model outputs to derive actionable insights for reducing churn.

#### Results
The most significant factors driving churn included **Churn Category (Not Applicable, Competitor, Dissatisfaction)**, **Customer Service Calls**, and **Contacted Support**. The **Random Forest** model emerged as the best-performing model, with a **ROC-AUC score of 0.99998**. It provides a strong balance between accuracy and generalizability, making it suitable for real-world applications. **SVC** and **KNN** also performed well but showed signs of potential overfitting.

#### Next Steps
- **Implement Targeted Retention Strategies**: Focus on reducing churn driven by competitors and dissatisfaction, improve customer service quality, and offer incentives for customers at high risk of churn.
- **Threshold Tuning**: Experiment with adjusting the decision threshold to better balance precision and recall for churn predictions.
- **Further Model Optimization**: Consider using advanced models like XGBoost or LightGBM, and apply cross-validation for better generalization.

#### Outline of Project

- [Link to notebook 1]() - Data Cleaning and Preprocessing
- [Link to notebook 2]() - Exploratory Data Analysis (EDA) and Feature Engineering
- [Link to notebook 3]() - Model Building, Evaluation, and Interpretation

##### Contact and Further Information
For any questions or further information, feel free to contact ahachani@yahoo.com. Additional details and project documentation are available upon request.
