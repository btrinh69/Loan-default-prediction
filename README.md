# Loan-default-prediction
This project build a machine learning model which predict possible defaulters based on their historic data

## Context
An organization wants to predict who possible defaulters are for the consumer loans product. They have data about historic customer behavior based on what they have observed. Hence when they acquire new customers they want to predict who is riskier and who is not.

## Data
The following values were provided at the time of the loan application.


|Column|Description|Type   |
| -----|-----------| -----|
|income|Income of the user|int|
|age|Age of the user|int|
|experience|Professional experience of the user in years|int|
|profession|Profession|string|
|married|Whether married or single|string|
|house_ownership|Owned or rented or neither|string|
|car_ownership|Does the person own a car|string|
|risk_flag|Defaulted on a loan|string|
|currentjobyears|Years of experience in the current job|int|
|currenthouseyears|Number of years in the current residence|int|
|city|City of residence|string|
|state|State of residence|string|

## Task
Build a model to predict possible defaulters based on the data provided. The evaluation metrics are:
- `roc_auc_score`
- `accuracy`

## Files
- `full_notebook.ipynb`: The notebook which performs all parts of the tasks ranging from EDA, model development, and error analysis. This notebook can be used to reproduce the results
- `full_notebook.html`: The html version of the full notebook which is used to display the results (pandas-profiling and pipeline diagram) without having to run the notebook again
- `data`: the directory which contains the data files
