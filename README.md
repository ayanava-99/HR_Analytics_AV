# HR_Analytics_AV
<h2>Problem Statement:</h2>

***
Your client is a large MNC and they have 9 broad verticals across the organisation. One of the problems your client is facing is around identifying the right people for promotion (only for manager positions and below) and preparing them in time. -Currently the process, they are following is:
- They first identify a set of employees based on recommendations/ past performance
- Selected employees go through the separate training and evaluation program for each vertical. These programs are based on the required skill of each vertical
- At the end of the program, based on various factors such as training performance, KPI completion (only employees with KPIs completed greater than 60% are considered) etc., employee gets promotion

For the above mentioned process, the final promotions are only announced after the evaluation and this leads to delay in transition to their new roles. Hence, the company needs your help in identifying the eligible candidates at a particular checkpoint so that they can expedite the entire promotion cycle. 
***


![download](https://github.com/ayanava-99/HR_Analytics_AV/blob/main/download.png)
***

They have provided multiple attributes around Employee's past and current performance along with demographics. Now, The task is to predict whether a potential promotee at checkpoint in the test set will be promoted or not after the evaluation process.

___

<h3><center> Dataset Description:</center></h3>


| Variable | Definition | 
| :- | :- | 
| **employee_id** | Unique ID for employee 
| **department** | Department of employee 
| **region** | Region of employment (unordered) 
| **education** | Education Level 
| **gender** | Gender of Employee 
| **recruitment_channel** | Channel of recruitment for employee
| **no_of_trainings** | no. of other trainings completed in previous year on soft skills, technical skills etc. 
| **age** | Age of Employee 
| **previous_year_rating** | Employee Rating for the previous year
| **length_of_service** | Length of service in years
| **KPIs_met >80%** | if Percent of KPIs(Key performance Indicators) >80% then 1 else 0 
| **awards_won?** | if awards won during previous year then 1 else 0
| **avg_training_score** | Average score in current training evaluations 
| **is_promoted** | (Target) Recommended for promotion 


## Python environment [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1WeOxH4cfcD9Lo3PgaH22J3nalNd3J-MW?usp=sharing)
Give it a try, no need of installations!

## Link to Problem Statement
[HR Analytics](https://datahack.analyticsvidhya.com/contest/wns-analytics-hackathon-2018-1)

Checkout more such Hackathons at [Analytics Vidhya](https://datahack.analyticsvidhya.com/contest/all/)

## Notes
If you still insist to run it on your PC, the `requirements.txt` file should list all Python libraries that the notebook
depends on, please install them on a virtual env using:

Anaconda:
```
$ conda create --name newenv --file requirements.txt
```
Python3
```
$ pip3 install -r requirements.txt
```
