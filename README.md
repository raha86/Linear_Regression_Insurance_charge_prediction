# Linear_Regression_Insurance_charge_prediction

## Dataset link:
https://drive.google.com/drive/folders/1xa3GM_M-NfZIYZN4vMXlwsYEzvRoJREE?usp=sharing

## Problem Statement

Insurance premiums are often based on various factors that in the end decide the amount that will be covered from the insurance company. As a data analyst/scientist you are given a set of historical data for an organizations customers and the respective charges that were levied upon the insurance company.

The data gives you the information about the users including their age, sex, bmi, hospitalization history, annual income, etc. Analyze and gather insights from the data and create a linear regression model that will best predict the insurance charges for a new set of data.

## Dataset Information
![image](https://github.com/user-attachments/assets/08b051bf-cb17-4cc8-a57d-7f8ed50032b3)

## Steps Performed:

### 1. Exploratory Data Analysis
   * Checked distribution of variables
   * Checked for measure of peakedness and outlier analysis using boxplots \n
   * Checked relationship between the dependent and independent variables using a pairplot \n

### 2. Data Imputation:
#### Approach for data imputation:
1. Replaced the null values with the mean in columns where it shows close to a normal distribution i.e age, bmi, claim_amount, past_consultations, num_of_steps.
2. For the distributions that shows a skewed distribution, we replaced the null values with the median of the column.

### 3. Feature Selection for Data Modeling:
* Used correlation matrix and heatmap to visualize the correlation of the independent variables with the target variable.
  
### 4. Data Preprocessing And Model Training:
* Standardizing the features:
Normalizing the features so that the samples will have the same mean and standard deviation. (Used StandardScaler to achieve this)

* Model Building

* Model Evaluation:
Used R2 score to measure the performance. Achieved 97% accuracy.

### 5. Visual Representation:

![image](https://github.com/user-attachments/assets/5050cd19-e7f1-44e8-8ba6-eee3412e9f47)


