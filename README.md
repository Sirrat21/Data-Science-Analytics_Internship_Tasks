# Data-Science-Analytics_Internship_Tasks

**Task-1 – Iris Dataset Exploration & Visualization**

**1. Project Title**

Exploring and Visualizing the Iris Dataset using Python

**2. Objective**

The main objective of this project is to understand how to load, explore, summarize, and visualize a dataset using Python libraries such as pandas, matplotlib, and seaborn.

**3. Dataset**

**Name:** Iris Dataset

**Format:** CSV

**4. Description:**
The dataset contains measurements of iris flowers including:
1. Sepal Length
2. Sepal Width
3. Petal Length
4. Petal Width
5. Species (Setosa, Versicolor, Virginica)

**5. Tools & Libraries Used**
1. Google Colab
2. Python
3. pandas
4. matplotlib
5. seaborn

**6. Steps Performed**

**Data Loading**

    •	Uploaded and loaded the dataset using pandas
**Data Inspection**
    •	Checked dataset shape
    
    •	Viewed column names
    
    •	Displayed first few records
**Data Summarization**
    • Used .describe() to analyze statistical information
**Data Visualization**
1. **Scatter Plot:** To analyze relationships between variables
2. **Histogram:** To study data distribution
3. **Box Plot:** To detect outliers and understand spread

**Key Learnings**
•	How to load and inspect datasets using pandas

•	Understanding dataset structure and statistics

•	Creating meaningful visualizations

•	Identifying patterns, relationships, and outliers in data

**Conclusion**

This project provided hands-on experience in data exploration and visualization. It helped in understanding how graphical representations can simplify complex data and reveal useful insights.

**How to Run**

•	Open Google Colab

•	Upload the dataset (Iris.csv)

•	Run the provided Python code step by step

•	View outputs and visualizations


**Task 2: Loan Default Prediction**
**Objective**
The goal of this project is to predict whether a loan applicant is likely to default on a loan using machine learning techniques.
________________________________________
**Dataset**
•	Source: Kaggle Loan Prediction Dataset
•	The dataset contains applicant details such as:
o	Applicant Income
o	Loan Amount
o	Education
o	Credit History
o	Loan Status (Target Variable)
________________________________________
**Technologies Used**
•	Python 
•	Pandas & NumPy (Data Processing)
•	Matplotlib & Seaborn (Visualization)
•	Scikit-learn (Machine Learning)
________________________________________
Project Workflow
1.	Data Preprocessing
•	Handled missing values:
o	Numerical → Filled with median
o	Categorical → Filled with mode
•	Converted categorical variables using One-Hot Encoding
________________________________________
**Exploratory Data Analysis (EDA)**
•	Visualized:
o	Loan Amount Distribution
o	Income vs Loan Status
o	Education vs Loan Status
•	Identified patterns and relationships between features
________________________________________
**Model Building**
•	Applied classification algorithms:
o	Logistic Regression
o	Decision Tree
________________________________________
**Model Evaluation**
•	Accuracy Score used to measure performance
•	Confusion Matrix used to analyze predictions:
o	True Positives
o	True Negatives
o	False Positives
o	False Negatives
________________________________________
Results
•	The model was able to predict loan default with reasonable accuracy
•	Confusion matrix provided insights into classification errors
•	Model can assist in identifying high-risk applicants




**Task 3: Customer Churn Prediction**
**Objective**
 
 Predict whether a customer will leave the bank using machine learning.

**Dataset**

Churn Modelling Dataset with customer details like age, gender, balance, and activity status.
**Target:** Exited (0 = Stay, 1 = Churn)

**Preprocessing**

•	Removed unnecessary columns 
•	Encoded categorical features (Gender, Geography) 
•	Split data into training and testing sets 
•	Applied feature scaling 

**Model Used**
•	Random Forest Classifier 
**Evaluation**
•	Accuracy Score 
•	Confusion Matrix 
**Key Insights**
•	Important factors affecting churn: 
o	Age 
o	Balance 
o	Activity status 

**Conclusion**
Random Forest effectively predicts customer churn and helps identify key factors influencing customer retention.

