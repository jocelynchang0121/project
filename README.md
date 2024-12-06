# Jocelyn_portfolio

# Home Credit Loan Default Analysis

# Business Problem Overview
Home Credit serves underserved clients with limited or no credit history, making loan repayment assessment challenging. The company collects data on clients' unique characteristics to address this. Financial impacts include a median loss of $24,412 from defaults and a median revenue loss of $23,800 from incorrect loan rejections. Both situations negatively affect operational efficiency.

# Key Findings from Our Analysis
Our analysis identified that the top-performing model, XGBoost, highlighted four key predictors: Ext_Source_3, Ext_Source_2, Days_Birth, and Amt_Annuity. These factors are crucial for assessing creditworthiness. Notably, Days_Birth suggests that age could play a significant role in repayment ability, with younger individuals potentially facing more challenges in loan repayment, possibly due to being earlier in their financial journey. This finding indicates that Home Credit may want to focus more closely on these variables when evaluating loan applications to improve risk assessment and decision-making processes.

# Proposed Solution to the Business Problem
Our solution prioritizes customer segmentation by focusing on high-creditworthy and underbanked segments identified through analysis. This targeted approach enables more efficient resource allocation and better service to underserved populations. Additionally, we aim to optimize lending models by leveraging predictive analytics to refine risk assessment processes and tailor product offerings to meet the needs of these segments. Finally, we recommend enhancing digital channels by investing in digital onboarding, which will streamline the customer experience, reduce processing costs, and improve overall efficiency in servicing new and existing clients.

# Expected Benefits of Our Solution
Our solution would enhance financial inclusion, build customer trust, and improve operational efficiency. It would minimize losses, strengthen risk management, and enable more effective pricing strategies.

# My Contributions to the Project
My contribution to the project included running multiple machine learning models, such as Logistic Regression (both with and without regularization), Artificial Neural Networks (MLP), Naive Bayes, and KNN models. I was also responsible for feature engineering to enhance model performance. Additionally, I prepared and edited the final notebook, including the creation of a Table of Contents for easy navigation. I visualized model performance through ROC-AUC curves and confusion matrices, and implemented resampling techniques to improve the model's robustness. Finally, I tested the models on the final test set and contributed to the Kaggle results submission.

# Challenges Faced During Model Implementation
During the modeling process, one of the challenges we encountered was the need for resampling the data. For example, with the Random Forest model, we implemented undersampling, which led to significantly better performance. The model achieved a training accuracy of 99.99% and a validation accuracy of 95.39%, indicating strong generalization without overfitting, as the drop between training and validation accuracy was only 4.6%. This performance was notably better than the majority classifier, which had an accuracy of 91.91%. In contrast, undersampling with the Decision Tree model was less effective. It showed perfect accuracy on the training set (100%) but a drop to 90.97% on the validation set, suggesting some overfitting with a decline of 9.03% between the two sets. This discrepancy highlighted the challenges of balancing model complexity and generalization.

# Key Learnings from the Project
I learned how to effectively implement multiple machine learning models, handle feature engineering, and visualize model performance. We also faced challenges with resampling data, as undersampling improved Random Forest performance significantly, but less so for the Decision Tree model, highlighting the importance of balancing model complexity and generalization. This experience reinforced the significance of using data-driven insights to make informed business decisions, especially when addressing critical issues like creditworthiness and risk management.
