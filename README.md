# Home-Credit-Analysis

## Summary of the business problem and project objective 
**1. Business Problem:**
The business problem for the Home Loan Credit Risk analysis project is to build a predictive model that can assess the credit risk of individuals applying for home loans. Home Credit wants to minimize its risk exposure by identifying potential borrowers who are likely to default on its home loans. By analyzing historical loan data and borrower information, the goal is to create a model that accurately predicts whether a loan applicant is likely to default or not.

**2. Project Objective:**
The project's objective is to develop a machine learning model that can effectively predict the creditworthiness of loan applicants for home mortgages. The model will be trained on historical loan data containing various attributes such as income, marital status, employment history, loan amount, and other relevant features. By using this historical data, the model will learn to recognize patterns and correlations that are indicative of high or low credit risk.

## Solution to the business problem
In our Home Credit Risk Analysis project, based on extensive Exploratory Data Analysis (EDA) and robust modeling techniques, we have identified a specific group of target customers that could potentially serve as a key solution to our business problem. These ideal clients exhibit several favorable characteristics that make them less risky and more likely to fulfill their credit obligations.

Our analysis has highlighted the following key attributes that define our preferred target customers:

1. *Ownership of a Car:* Clients who own a car tend to demonstrate a higher level of financial stability and responsibility. The possession of a valuable asset like a car suggests a stronger ability to manage financial commitments.

2. *Marital Status:* Married individuals tend to exhibit more financial stability compared to single applicants. The presence of a stable family structure often translates into better financial management and reduced credit risk.

3. *Higher Education:* Clients with a higher education background have shown a tendency towards better financial planning and a deeper understanding of credit responsibilities. This demographic is likely to be more reliable in repaying their loans.

4. *Businessmen:* Business owners and self-employed individuals are often more financially independent and disciplined in managing their finances. Their entrepreneurial nature implies a higher likelihood of credit repayment.

5. *Ownership of a House or Apartment:* Homeowners tend to possess a higher level of financial security and commitment. Owning a property signifies a greater sense of stability, making them potentially more dependable borrowers.

By targeting clients with these characteristics, we can potentially mitigate credit risks and enhance the overall credit portfolio performance. Focusing on these specific demographics can result in a higher percentage of successful loan repayments, ultimately reducing the incidence of defaults and improving the overall profitability of our lending operations.

However, it is essential to emphasize that while targeting these customer segments may reduce credit risk, it is crucial to maintain a balanced approach in customer acquisition. Proper evaluation of individual creditworthiness, income verification, and other relevant factors should always be conducted to ensure responsible lending practices.

In conclusion, by honing our efforts on clients who own a car, are married, have pursued higher education, or are businessmen, and those who own a house or apartment, we can make significant strides in managing credit risk effectively and achieving our business objectives in the Home Credit domain.

## My Contribution
I focused on tackling issues with missing data and outliers in the dataset and proposed practical solutions to these challenges. This included an exploratory data analysis phase where I conducted visualizations and generated summary tables to understand the data better. To refine the quality and representation of the dataset, I utilized robust category encoding and sampling techniques. This process involved transforming categorical variables and implementing under/oversampling methods to address any class imbalance in the data. I experimented with several machine learning algorithms, such as Logistic Regression, Random Forest, Gradient Boosting, and Ensemble modeling using a Voting Classifier. Among these, the Random Forest model yielded the most promising results, achieving a Kaggle score of 0.66. This score was the result of systematic hyperparameter optimization. To further improve our predictions, I explored Ensembling, which allowed me to combine the strengths of Logistic Regression, Random Forest, and Gradient Boosting models. The ensemble model then generated potentially more accurate predictions based on inputs from these individual models. After this phase, I returned to the cleaned data to conduct additional modeling attempts. I evaluated each model's performance by comparing their accuracy, precision, recall, and F1 scores. This comparison helped me determine the most effective algorithm for this specific dataset.

## Business value of the solution
**1. Default Prevention:** Assuming the average mortgage in a portfolio is $200,000 and 1000 loans per year are granted. If, historically, 2% of loans defaulted and this model could prevent even 50% of these, it would save the company 0.020.51000*$200,000 = $2,000,000 per year.

**2. Improved Customer Satisfaction:** This one is harder to quantify, but faster loan processing might increase the customer base. If even 1% more customers are attracted due to improved satisfaction, for a company processing 10,000 loans annually, this could equate to 100 additional loans. If 1% origination fee is earned on each loan of $200,000, this equates to 100*$200,000*0.01 = $200,000 per year.

**3. Informed Decision-Making & Regulatory Compliance:** This is difficult to quantify without concrete numbers. But better risk management can lead to improved products, fewer regulatory fines, and a better reputation.

## Difficulties
**1. Imbalanced Data:** The dataset was imbalanced, meaning one class had many more instances than the other. This is a common issue in credit risk modeling, where the majority of customers do not default on their loans. An imbalanced dataset can lead to a model that is biased toward predicting the majority class, which can result in a high number of false negatives or false positives. Techniques such as under-sampling, over-sampling, or SMOTE (Synthetic Minority Over-sampling Technique) had to be used to address this issue.

**2. Outliers:** In the home credit risk analysis project, one of the critical tasks involved dealing with outliers in the dataset. Initially, we opted for normalization techniques to scale the data, but after thorough analysis and consideration of the data characteristics, we decided to employ the winsorization method instead. This approach proved to be more effective in mitigating the impact of extreme values while preserving the underlying information in the data. Winsorization involves capping or flooring the extreme values to a certain percentile, thereby reducing the influence of outliers on the overall analysis. This decision was based on the plausibility that extreme data points could significantly skew risk assessment models, leading to inaccurate predictions. By adopting winsorization, we achieved a more robust and reliable credit risk analysis, providing better insights for decision-making in the lending process.

**3. Missing Data:** One of the challenging tasks was handling missing values in the dataset. In certain columns, over 65% of the data was missing, which posed a significant issue for accurate analysis. To address this, we employed various imputation methods to fill in the missing values and make the dataset complete.

**4. Feature Selection:** Deciding which columns to drop and which to impute was challenging. Dropping a column means losing all information in that column, which could be important for the model. On the other hand, imputing can introduce bias or distortion. A thorough analysis had to be done on each column to decide whether it was more beneficial to drop it or impute it. This required understanding the meaning and relevance of each column, the extent and nature of missing values, and the potential impact on the model's performance.

## Learnings 
I have acquired skills in transforming categorical variables and sampling techniques to address the class imbalance, enhancing the quality and representation of the dataset. I have gained practical experience in implementing and optimizing various machine learning algorithms like Logistic Regression, Random Forest, and Gradient Boosting. I have also appreciated the power of Ensemble modeling and understood the significance of various performance metrics beyond accuracy, such as precision, recall, and F1 scores. I have faced the complexities and imperfections of real-world data, as opposed to cleaned and simplified datasets typically used for learning. 

This being a team project, I have learned the value of collaboration, the division of tasks based on strengths, and how to combine individual efforts for a common goal. I have honed my ability to work effectively in a team. I have improved my ability to communicate technical findings effectively to my team members, facilitating the sharing of insights and collaborative decision-making. Encountering and overcoming challenges like imbalanced data and outliers has enhanced my problem-solving skills. Meeting deadlines, prioritizing tasks, and coordinating efforts within the team have provided me with a good grasp of project management.
