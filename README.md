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
![image](https://user-images.githubusercontent.com/74996807/101258277-73093900-36ef-11eb-90f6-7fa3240d532d.png)



-> From the boxplot and histogram, we see that most values lie between 70k to 130k

-> The salary histogram plot has right skewness



• Correlation Matrix

![image](https://user-images.githubusercontent.com/74996807/101258541-1f97ea80-36f1-11eb-92ca-ef1bf16a4af6.png)


->The heat map shows that degree and major are highly correlated.

->The salary is normally distributed.


• Job type

![image](https://user-images.githubusercontent.com/74996807/101258626-b5cc1080-36f1-11eb-9d3e-671a5fe47e1c.png)


->positive correlation between job Type and salary.

->Highest salaries are CEO, followed by CTO and CFO. The janitor’s salaries are lowest.

->Distributions appear normal.


• Major

![image](https://user-images.githubusercontent.com/74996807/101258666-18bda780-36f2-11eb-8520-1163d20ecb02.png)


->Peoples with majors such as engineering, business and math have higher salaries.

->No major peoples have less salaries.

. Degree

![image](https://user-images.githubusercontent.com/74996807/101258763-9aadd080-36f2-11eb-9f2d-64c9f96106df.png)


->Masters and doctors correspond to having higher salaries.

->The high school and none peoples have less salaries.

->Salary seems to increase with the advance in degree.


• Industry
![image](https://user-images.githubusercontent.com/74996807/101258814-fe37fe00-36f2-11eb-8b72-bf6b09915192.png)


->Oil and Finance pay the highest.
->Education industry seems to pay lowest
 
• Develop

Linear Regression 383

Random Forest 376

GradientBoostingRegressor 362

• Distribution plot

![image](https://user-images.githubusercontent.com/74996807/101258859-4fe08880-36f3-11eb-824c-8d580662f5e1.png)



->Distribution plot of actual value and predicted value.

-> We can see that the actual values and predicted values are not that different. The mean of the predicted values seems higher and the range seems low
 
Deploy

![image](https://user-images.githubusercontent.com/74996807/101258922-ab127b00-36f3-11eb-98c7-14b368cb1873.png)

->Create a csv file

->According to the GradientBoostingRegressor model lower salary is higher recruitment. Janitors salary is less , so the importance is high.
