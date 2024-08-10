# Oil-Spill-Statistical-Analysis-with-ML-Algorithms

## Oil Spill Prediction and Analysis

### Introduction
This project focused on developing a comprehensive system for oil spill prediction and analysis. By leveraging machine learning and deep learning techniques, the study aimed to identify oil spills through image analysis and predict future occurrences based on historical data.

### Dataset 1: Oil Pipeline Accidents (1)
The database contains information on every reported oil pipeline leak or spill from 2010 to 2017 across various states in the United States. This dataset is in tabular format; it is a csv file which contains 48 columns and 2795 rows of data. According to acknowledgement of Kaggle, these oil pipeline accident reports were collected and published by the DOT's Pipeline and Hazardous Materials Safety Administration and available for public use.
### Data Cleaning and Wrangling 

![image](https://github.com/user-attachments/assets/130c9b27-665e-4b8c-a95e-0558dd19abf4)

### Exploratory Data Analysis and visualization 

![image](https://github.com/user-attachments/assets/00cc84ad-26e6-4898-b148-4e2170725a8d)


![image](https://github.com/user-attachments/assets/ab851639-3c97-4b71-b941-6da846fec180)

### Classification Models
To predict categorical outcomes such as whether a spill resulted in a liquid explosion, ignition, or pipeline shutdown, several classification models were employed. These models learned patterns in the data to classify instances into predefined categories.
##### Logistic Regression: This model estimates the probability of an event occurring based on a set of independent variables.   
##### Decision Trees: This model creates a tree-like structure to classify instances based on a series of decision rules.
##### Random Forest: An ensemble method that combines multiple decision trees to improve prediction accuracy and reduce overfitting.   
##### Naive Bayes: This model assumes independence between features and calculates probabilities based on Bayes' theorem.1

![image](https://github.com/user-attachments/assets/1a57c008-cabc-4801-bb6c-1df0f1cc2fa9)

Random Forest consistently outperformed the other models in classifying spill-related outcomes, indicating its effectiveness in capturing complex relationships within the data.

### Regression Models
To predict numerical values such as spill quantity, liquid recovery, and associated costs, regression models were utilized. These models aim to establish a relationship between independent variables and a continuous dependent variable.   

##### K-Nearest Neighbors (KNN): This model predicts the value of a data point based on the values of its closest neighbors. 
##### Random Forest: While primarily used for classification, Random Forest can also be employed for regression tasks.   
##### XGBoost: A gradient boosting algorithm known for its performance in various machine learning tasks, including regression.   
##### AdaBoost: Another boosting algorithm that combines multiple weak learners to create a strong predictive model.   

![image](https://github.com/user-attachments/assets/ba2978a8-41eb-4f55-874a-b5fb699a65d3)


XGBoost demonstrated superior performance in predicting liquid recovery and total costs, while KNN excelled in estimating spill quantity. These findings highlight the importance of selecting appropriate models based on the specific prediction task.

### Conclusion
The research presented in this study aimed to develop a robust framework for oil spill prediction and analysis. By combining image analysis, statistical analysis, and machine learning techniques, the project sought to address critical challenges associated with oil spills.
The application of classification models to historical oil spill data proved successful in identifying key factors contributing to events such as liquid explosions, ignitions, and pipeline shutdowns. Random Forest emerged as the most effective classifier for these outcomes, demonstrating its ability to capture complex relationships within the data.
Regression models were employed to predict numerical variables, including spill quantity, liquid recovery, and associated costs. XGBoost emerged as a superior model for predicting liquid recovery and total costs, while KNN demonstrated effectiveness in estimating spill quantity.
The findings of this study contribute significantly to the understanding of oil spill patterns and impacts. The developed models offer potential for enhancing oil spill prevention, response, and recovery efforts. However, further research is warranted to refine the models, incorporate additional data sources, and explore the integration of real-time data for improved prediction accuracy.
By providing valuable insights into oil spill characteristics and potential consequences, this research represents a step forward in mitigating the environmental and economic impacts of these catastrophic events.
### References
1.	Oil pipeline accidents, 2010-present. (n.d.). Retrieved May 05, 2023, from https://www.kaggle.com/datasets/usdot/pipeline-accidents 
