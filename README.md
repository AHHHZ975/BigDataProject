# SOEN471 - Sofvie Project 8 - Team 34

Training programs are crucial in many workplace environments to ensure that employees have up-to-date skills and knowledge about certain procedures. Safety training in particular greatly prevents the risk of an incident occurring by increasing awareness of safety protocols in the event of a possible hazard.

Sofvie [1] is a company that focuses on efficiency and employee safety by adopting a proactive approach to employee training. Our goal with this project is to use big data and machine learning techniques to analyze employees and training to make classifications based on training completion rates.

Our dataset has been provided to us by Sofvie in the form of various schemas and template SQL scripts. By running SQL queries we determined that it contains the information of 2001 employees, 2 different training types that branch out into 776 unique training codes, and a pairing of 33,115 completed training amongst employees. Our dataset features include:
- Employee table 
  - Employee number [varchar]
  - Employee position id [int]
  - Start/End date [datetime]
- Employee training table
  - Training type [int]
  - Training code [int]
  - Trainings completed by the employee [int]
- Person
  - Generation ['Boomer', 'Gen X', 'Millenial', 'Gen Z']
  - Gender [varchar]

Due to receiving our dataset on quite short notice (02/13/2023), more features will come to light as we make progress. We may potentially ask Sofvie to provide us with other relevant features such as ‘employee pay grade’ or ‘training duration’ that could play a role in employee willingness to complete training.

Based on our dataset, we will seek to answer the following research questions:

1- What factors increase the likelihood of an employee having higher training completion rates?

2- What are the features in common for employees with different completion rates?

3- What are the common factors in training with high completion rates versus those with low completion rates?


We decided to approach these research questions from a clustering model point of view. Using the number of completed training, we will cluster employees and analyze what common features can be found amongst each group and report on factors that influence a higher training completion. From a different perspective, we will cluster training and see what common attributes can be found to gain insight into trainings that resonate well with employees. To achieve both goals, we will use two algorithms: k-means and hierarchical clustering. After evaluating the clusters with both algorithms we will compare the efficiency and performance of both algorithms.


References:

[1] https://sofvie.com

## Team Members 
- Daria Denejkina
- AmirHossein Zamani
- Ali Sabaghpourfard
- Alan Matthew Vadlakunta

