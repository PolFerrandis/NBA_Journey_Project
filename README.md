# The NBA Journey

## Can we predict future NBA All Stars from their college performance?



   ![image](https://user-images.githubusercontent.com/88676121/146384858-ab1bc6a4-4d89-4680-af96-69abca697a18.png)


## Table of contents
- [Project Brief](https://github.com/PolFerrandis/NBA_Journey_Project/blob/main/README.md#project-brief)
- [Data](https://github.com/PolFerrandis/NBA_Journey_Project/blob/main/README.md#data)
- [Process & Tools](https://github.com/PolFerrandis/NBA_Journey_Project/blob/main/README.md#process--tools)
- [Visualization](https://github.com/PolFerrandis/NBA_Journey_Project/blob/main/README.md#visualization) 
- [Key Take Aways](https://github.com/PolFerrandis/NBA_Journey_Project/blob/main/README.md#key-take-aways)

## Project Brief
**Scenario**: In the last years we have seen that NBA teams who win the title, have at least 2-3 allstar players in their roster. The draft selection is a great opportunity to build strong team, but at the same time it entails some risks for the franchises.

**Challenge**: We want to be able to predict what college basketball players have potential to become all stars.


## Data

Leveraging on the [data](https://github.com/PolFerrandis/NBA_Journey_Project/tree/main/Data) we have found, we used Python to explore the relationships between features.

The data sets used consists of:

- 17.000 College players statistics from 2008 to 2021, taking the single season stats for when the players declared their eligibility for the NBA draft.

- NBA Allstar rosters from 2008 to 2021

- NBA Rookies 2021 



For further details on all features, please refer to the [notebook](https://github.com/PolFerrandis/NBA_Journey_Project/tree/main/Jupyter%20Notebooks)


## Process & Tools

**Process**

I decided to create 2 separate prediction models for 2 different purposes:


1 - Model to predict whether a college player will be drafted

2 - Model to predict whether a college player will become a future all star



Both model included the below steps:


- Dataset preparation which involved web scrapping

- EDA: assessment of dataframe to prepare for cleaning

- Data cleaning & wrangling in Python
    
- Machine Learning Model: using scikit learn and logistic regression with the smote method to balance data

**Tools**

Database: [CSV file](https://github.com/PolFerrandis/NBA_Journey_Project/tree/main/Data)

Vizualizations: seaborn / matplotlib

Code: [Jupyter Notebook](https://github.com/PolFerrandis/NBA_Journey_Project/tree/main/Jupyter%20Notebooks) 


## Visualization


_**Data visualization**_

<img width="1027" alt="Screenshot 2021-12-16 at 15 35 59" src="https://user-images.githubusercontent.com/88676121/146391651-74bd2b09-0423-4963-94e0-ae3ac7efcb7e.png">


<img width="1028" alt="Screenshot 2021-12-16 at 15 39 00" src="https://user-images.githubusercontent.com/88676121/146399267-50dd3595-4c7d-42a3-94c6-bd9991991d56.png">


<img width="1034" alt="Screenshot 2021-12-16 at 15 36 29" src="https://user-images.githubusercontent.com/88676121/146391704-77b541b5-931a-415b-bb04-19774a7c485c.png">


<img width="1025" alt="Screenshot 2021-12-16 at 15 36 45" src="https://user-images.githubusercontent.com/88676121/146391726-e4485d51-5da4-478b-9737-8a16f83d9dbf.png">




**_Confusion Matrix_**


Model 1

<img width="403" alt="Screenshot 2021-12-16 at 15 46 04" src="https://user-images.githubusercontent.com/88676121/146393375-b8b1b030-7b6b-4c8d-b5e5-2550e22ef028.png">



Model 2

<img width="403" alt="Screenshot 2021-12-16 at 15 43 20" src="https://user-images.githubusercontent.com/88676121/146392936-279b3f86-5c7e-433a-b3bc-4f0f1f916920.png">



## Key Take Aways

Our 1st model can predict whether a college player will be drafted with an accuracy of more than a 94%.

Our 2nd model can predict whether a college player will become an allstar with an accuracy of more than a 87%.

