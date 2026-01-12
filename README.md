## Obesity Level Prediction Project  
### Problem Statement  
Obesity is a major public health challenge linked to chronic conditions such as type 2 diabetes and cardiovascular disease. Traditional assessment methods, particularly Body Mass Index (BMI), are widely used but often fail to capture the complex influence of demographic, behavioral, and lifestyle factors,
leading to potential misclassification of obesity risk. Machine learning offers a data-driven approach capable of modeling complex relationships among multiple risk factors to improve obesity classification.  

### Objective
This project aims to develop and evaluate machine learning models that predict an individual’s obesity category (NObeyesdad) using demographic attributes, dietary habits, physical activity, and lifestyle behaviors, which can be used in supporting early intervention and informed healthcare decision-making.

### Scope
- The project invoveled various steps as indicated:
1.   Data preprocessing
2.   exploratory data analysis
3.   Feature engineering ( was to include the calculation of Body Mass Index but wasnt much useful therefore got ingored)
4.   Application of supervised machine learning classification techniques (Naive Bayes, Decision Trees, Random Forests, and Gradient Boosting).
5.    Model performance assessment using evaluation metrics including accuracy, precision, recall, F1-score, confusion matrices, and ROC–AUC curve.

- Hyperparameter tuning was also applied to improve model generalization and ensure robust performance.
-  The project emphasized on comparative analysis to identify the most effective model for obesity classification, The findings aim to demonstrate the potential of machine learning in supporting obesity risk assessment and healthcare decision-making.

#### Feature Importance
The best performing model had individual features performing as indicated below:  

![feature importance](https://github.com/Dorice97/Obesity-Level-prediction-Model/blob/main/feature%20importance%20-%20obesity%20model.png)

### Results
Model performance was as indicated bellow based on different classification models used:  

![Model performance](https://github.com/Dorice97/Obesity-Level-prediction-Model/blob/main/model%20performance%20scores.png)  


### Scores interpretation  
- Decision tree- has overfitting and showed sensitivity to hyperparameters  
- Naive Bayes- has low accuracy, underfitted  
- Random Forest- displayed high accuracy , robust to noise and stable  
- Gradient Boosting- Highest accuracy level, best generalization with excellent biase variance trade-off

### Conclusion
- Among all evaluated models, Gradient Boosting achieved the highest tuned test accuracy (98.6%), indicating superior generalization performance. Although Random Forest also performed strongly, Gradient Boosting was selected as the final model due to its ability to capture complex nonlinear relationships in the data.




