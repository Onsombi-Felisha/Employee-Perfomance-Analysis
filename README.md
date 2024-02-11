# Employee-Perfomance-Analysis

## Table of Contents
[Project Overview](#project-overview)

[Analysis](#analysis)

[Univariate Analysis](#univariate-analysis)

[Bivariate Analysis](#bivariate-analysis)

[Coorelation Analysis](#coorelation-analysis)

[Machine Leaning Model](#machine-learning-model)

[Conclusions](#conclusions)

[Recommendations to improve employee perfomance](#recommendations-to-improve-employee-perfomance)

## Project Overview

The project is set to analyse the employee perfomance in INX Future Inc, which is a data analytics and automation solution provider.For the past 5 years, the company is rated among the best 20 employees. However, recently the company has seen the employee performance indexes are not healthy and this is becoming a growing concern among the top management. There has been increased escalations on service delivery and client satisfaction levels came down by 8 percentage points. The CEO decided to initiate a data science project , which aims to analyse the employee perfomance. The following goals and insights are expected from the project :
* Department wise performances
* Top 3 Important Factors affecting employee performance
* A trained model which can predict the employee performance based on factors as inputs. This will be used to hire employees
* Recommendations to improve the employee performance based on insights from analysis.

## ANALYSIS

The Dataset went through univariate and bivariate analysis to get more understanding on the data. Visualisations through histograms,pie charts and histoplots and coorelation analysis. Analysis per department by perfomance rating to satisfy the second goal.

### UNIVARIATE ANALYSIS
#### ENCODED COLUMNS
1.   Education Level - 12.3% of employees  have below college education , 19.9% have a college education level, 37.4 %have bachelor's degree and 26.8% have master's degree, 3.8% have Phd and 2.5% have others
2.   Environment Satisfaction - 19.2% of employees have low rating on environment satisfaction , 20.2% have a medium rating on environment satisfaction, 30.6 % have a high rating on environment satisfaction and 30.1% have a very high rating on environment satisfaction
3.   Job Involvement - 5.8% of the employees have a low rating on job involvement , 24.5% have a medium rating on job involvement, 60.3% have a high rating on job involvement and 9.3% have a very high rating on job involvement
4.   Job Satisfaction - 19.2% of the employees have a low level of job satisfaction, 19.8% have a medium level of job satisfaction, 29.5% have a high level of job satisfaction and 31.5% have a very high level of job satisfaction
5.   Relationship Satisfaction - 18.3% of the employees have low relationship satisfaction , 20.6% have a medium relationship satisfaction, 31.6% have a high relationship satisfaction and 29.6% have a very high relationship satisfaction
6.   Work Life Balance - 5.3%  have a bad work life balance , 60.6% have a better work life balance , 24.5% have a very good work life balance and 9.6% have the best work life balance
7.   Perfomance Rating - No employee has a low perfomance rating , 16.2% have a medium perfomance rating , 72.8% have a high perfomance rating and 11.0% have a very high perfomance rating
   
#### CATEGORICAL COLUMNS

1. The Gender distribution is  725 of Male employees and 475 of Female employees in the company.

2. The number of the educational backgrounds present in the employees is six backgrounds.That is Marketing, Life Sciences,Human Resources, Medical, Technical Degree, and Other.

3. Business Travel Frequency has 3 unique values with 900 employees have travelled rarely , while the least which is about 100 employees have not traveled and 2000 employees have travelled frequently
There are 19 unique values in the job role column.

4. The overall number of employees doing overtime is 360

5. The 1000 of employees are not having attrition in their work, while only 200 of employees in the company have attrition in their work

#### NUMERICAL COLUMNS
1. The age distribution is starting from 18 to 60 where the most of the employees are lying between 30 to 40 age count.
2. The distance from home to office is distributing from 0 unit to 30 unit which can be kilometre or mile. The most of the employees are coming from the range of 0 to 5 units.

3. Employees are worked in the multiple companies up to 8 companies where most of the employees worked up to 2 companies before getting to work here.

4. The hourly rate range is 65 to 95 for majority employees work in this company.

5. Most of Employees work up to 5 years in this company.

6. Most of the employees get 11% to 15% of salary hike in this company.
   
### BIVARIATE ANALYSIS
### DEPARTMENT WISE PERFORMANCE
Data Science and Development departments have the highest mean perfomance rating of 3 while the rest of the departments have a mean perfomance rating of 2.
In all departments those with a high salary percentage have a high perfomance rating.
Also a high level of environment satisfaction translates to high perfomance rating..

**Sales Department**

The Performace rating level 3 (High) is more in the sales department.

The male employees in the sales departmnent have a performance rating that is little bit higher compared to female.

Divorced have a rating of 3 while the married and single have a less rating.

The total work experience does not count the performance rating.

**Human Resources Department**

Most employees employees have a level 3 performance.

The older people are performing low in this department.

The female employees in HR department doing really well in their performance.

The total work experience does matter to performance in this department.

**Development Department**

 The largest number of employees are level 3 performers.

 Managers have the highest rating of 3

 The gender-based performance is nearly same for both.

**Data Science Department**

The highest average of level 3 performance is in data science department.

Businees Analyst in the department have highest rating

The overall performance is higher compared to all departments.

Male employees are doing good in this department.

**Research & Development Department**

The largest number of employees are level 3 performers.

Managers have the highest rating while Health Care Rep have the lowest rating.

The gender-based performance is nearly same for both.

The marital status does not matter in this department.

**Finance Department**

Male employees have a higher rating than their female counterparts.

Most employees have a rating of 3.


### COORELATION ANALYSIS

The Total years of experience and job level are having the higher correlation when comparing to all features.

Experience years at this company and years with the current manager has the second higher relation between these features.

Experience years at this company and experience in the current role makes the sense of correlation.

People who have more experience with the company has the more probability to get the promotion from the correlation between them.

In this plot, the age has the important role in the total number of work experience of an employee where it is a universal truth.

### Machine Learning Model

A TRAINED MODEL WHICH CAN PREDICT THE EMPLOYEE PERFORMANCE BASED ON FACTORS AS INPUTS

A machine learning model was trained using the data and the following are the accuracy scores:
1.   Random Forest classifier - 91%
2.   Decision Tree Classifier - 87%

Random Forest Classifier had the highest accuracy score(91%) therefore suitable for training and developing the model.

### Conclusions 

#### TOP 3 IMPORTANT FACTORS
One of the goals of this project is to find the important feature affecting the performance rating. The important features were predicted using the machine learning model(Random Forest Classifier) feature importance technique.From it the Machine Learning Model concluded that the following are the important features:
1. Employee Salary Hike Percentage
2. Employee Environment Satisfaction
3. Years Since the last Promotion


### Recommendations to improve employee perfomance

The recommendations are as follows:

1. To increase the employee salary hike percentage, salary hike will boost the employees morale thus increasing perfomance
2. The company needs to focus on the environment satisfaction, give the employees a proper environment that they are comfortable in  and are feeling positive.
3. Promotion will help the employees to achieve more performance by giving the chance to be more responsible and acquire leadership qualities.
4. Employee's work-life balance affects the performance rating. Therefore encourage and train employees on how to achieve proper work life balance to enhance employee’s perfomance in the company
