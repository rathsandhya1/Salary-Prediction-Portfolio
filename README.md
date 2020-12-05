# Salary-Prediction-Portfolio
 Aim

The aim of this project is to make accurate salary predictions that are based on existing current salaries, this helps the company to recruit and retain top talent. This model will help the company for offering competitive pay to existing and future employees while also keeping payroll expenses in check.


Technology/Libraries Use

Colab (Python 3)
Pandas
Numpy
Seaborn
Matplotlib
Sklearn Packages


Dataset Information
The data provided to us has been split in training and testing sets. The files included are training data (train_features_df), testing data (test_features_df) and a Target set (train_salaries_df) containing dependent salary feature.
The dataset includes available features or labelled columns for analysis are as follows:
Job ID/jobId: Given Job ID for the role
Company ID: Company ID for the respective Job ID advertised
job Type: Janitor, Manager, CEO, CFO etc.
Degree: High school, College, Master's etc.
Major: Physics, Biology, Maths etc.
Industry: Job ID's categorized industry such as Oil, Auto, Health, Finance etc.
Years of Experience: Required Experience for the role
Miles from Metropolis: Distance of the job location in miles from the nearest metropolitan city


Discover Part

Load Data
Clean Data-To provide more structured look to clarify the hidden information and analysed data.
Examine the data.
No duplicate data
Datasets don’t have null values.
Merged the train data.
Exploratory Data Analysis- In-depth Data Analysis, including summary statistics and visualization using regression, distribution, scatter and residual.
Identify correlation between all features by using label encoding.
Using correlation matrix.
Using Machine learning
• Linear Regression-This model is used to show or predict the relationship between two variables or factors.
• Random Forest-It is used for estimating missing data and maintains accuracy by reducing over fitting problem and shows it in decision trees.
• GradientBoostingRegressor- It helps in producing a model in the form of weak prediction models of decision trees and which could improve the base line model.

• Feature summary

• Salary feature Variable


-> From the boxplot and histogram, we see that most values lie between 70k to 130k

-> The salary histogram plot has right skewness



• Correlation Matrix

image

->The heat map shows that degree and major are highly correlated.

->The salary is normally distributed.


• Job type

image
->positive correlation between job Type and salary.

->Highest salaries are CEO, followed by CTO and CFO. The janitor’s salaries are lowest.

->Distributions appear normal.


• Major

image
->Peoples with majors such as engineering, business and math have higher salaries.

->No major peoples have less salaries.

. Degree

image
->Masters and doctors correspond to having higher salaries.

->The high school and none peoples have less salaries.

->Salary seems to increase with the advance in degree.


• Industry
image

->Oil and Finance pay the highest.
->Education industry seems to pay lowest
 
• Develop

Linear Regression 383
Random Forest 376
GradientBoostingRegressor 362

• Distribution plot

image

->Distribution plot of actual value and predicted value.

-> We can see that the actual values and predicted values are not that different. The mean of the predicted values seems higher and the range seems low
 
Deploy

image

->Create a csv file

->According to the GradientBoostingRegressor model lower salary is higher recruitment. Janitors salary is less , so the importance is high.
