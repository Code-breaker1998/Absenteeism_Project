# Analysis on Absenteeism to improve work performance

In this project, i want to share how absenteeism can impact for performance on organization and the problem of it.To solve these problem I used data analysis with the help of Python and Power Bi  and predict which employee will absent so organization can take action and prevent the problem using regression method (supervised learning).


## Feature Introduction

- Individual identification (ID)
- Reason for absence (ICD).
- Month of absence
- Transportation expense
- Distance from Residence to Work (kilometers)
- Age
- Work load Average/day
- Education (high school (1), graduate (2), postgraduate (3), master and doctor (4))
- Children
- Pets
- Body mass index
- Absenteeism time in hours (target)



## Data Analysis

#### Employee Information
![Employee Information](https://github.com/Code-breaker1998/Absenteeism_Project/blob/main/Images/Dashboard%201.png)

#### Daily Workload of Employee in Company
![Daily Worload of Employee in Company](https://github.com/Code-breaker1998/Absenteeism_Project/blob/main/Images/Dashboard%202.png)

#### Absenteeism of Employee with respect to Month and Year
![Absenteeism of Emplyee with respect to Month and Year](https://github.com/Code-breaker1998/Absenteeism_Project/blob/main/Images/Dashboard%203.png)


## Model Selection

I have used Logistic Regression for analysis and prediction of data


## Model Performance

| Labels | precision | recall   | f1-score |
|:------ | :-------- | :--------|----------|
| 0      | 0.81      | 0.77     | 0.79     |
| 1      | 0.69      | 0.74     | 0.72     |
|accuracy|           |          | 0.76     |



## Conclusion

- Reason 1 and Reason 3 has more weightage .
Therefore , reason like poisoning ,injuries are most common for absenteeism

- Employee having children and pets also provides weightage for absenteeism
- Also,Transport is a reason for which employee remain absent for hours
