# Breast Cancer Classification using Machine Learning
## Author:

Asra Tasneem Shaik  

## Date:

02-05-2024

## Programming Language & Version:

Python 3.8  

## Dependencies

This script relies on several non-built-in Python libraries:
- NumPy (`numpy`)
- pandas (`pandas`)
- Scikit-learn (`sklearn`)
- Matplotlib (`matplotlib`)
- Seaborn (`seaborn`)
- Plotly (`plotly`)

##  Description

This project harnesses advanced machine learning techniques to develop a predictive system capable of classifying breast cancer gene status into benign or malignant categories. Utilizing logistic regression and random forest models, the initiative processes the Breast Cancer Wisconsin (Diagnostic) dataset sourced from kaggle. The models are selected for their robustness and ability to handle complex, non-linear data structures effectively, making them ideal for the nuanced analysis required in medical diagnostics.


The effectiveness of the system is rigorously evaluated through a series of performance metrics including accuracy, Area Under the Curve (AUC), precision, recall, and F1 score. Achieving high accuracy rates—93.4% with logistic regression and 97.3% with random forest—the project demonstrates significant potential to enhance diagnostic accuracy in oncology. The outcome supports the broader integration of machine learning into clinical practice, offering a pathway towards more personalized and precise cancer treatment strategies based on reliable, data-driven insights.


## RESULT:
The project's results underscore the robust capabilities of machine learning models in distinguishing between benign and malignant breast cancer gene statuses. The logistic regression model attained an accuracy of 93.4%, showcasing its effectiveness in providing probabilistic outputs beneficial for nuanced clinical assessments. The random forest model, however, demonstrated superior performance with an accuracy of 97.3%, attributed to its ensemble methodology that mitigates overfitting and enhances data handling of complex, high-dimensional medical datasets.

Performance evaluations detailed both models’ proficiency:
- **Logistic Regression**: Offered valuable baseline accuracy and facilitated risk stratification through its probabilistic classifications.
- **Random Forest**: Excelled in accuracy and predictive reliability, benefiting from its ability to average decisions across numerous decision trees, which collectively reduce bias and variance in the model’s predictions.

Advanced metrics such as AUC scores highlighted the models' discriminative power, effectively measuring their capability to correctly classify positive and negative instances. The generated ROC curves and confusion matrices provided detailed insights into each model’s true positive and false positive rates, affirming the random forest model's capacity to minimize misclassifications. These outcomes validate the significant potential of integrating machine learning into oncological diagnostics, enhancing precision and reliability in identifying cancerous gene statuses.
