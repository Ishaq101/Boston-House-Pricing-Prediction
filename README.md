# Boston-House-Pricing-Prediction

<i>(!) Disclaimer: This project is for the purpose of Data Analytics/Machine Learning practice and using dataset from [kaggle](https://www.kaggle.com/c/boston-housing)</i>.
<br><br>
<b>Background</b>:
There is a new family (consist of Father, Mother, and 2 children) that want to move to Boston, and looking for secure and have many rooms house as their budget is around $25,000. This family have 2 children (one boy and one girl). They want a house that has 7 rooms (1 master bedroom, 2 child bedroom, 2 bathroom, 1 kitchen, 11 family room). The Father and Mother did not know much about property business, so they ask you as Data Scientist to help them make an engine to predict house pricing so they can considerate which one is the best to be purchased.
<br><br>
<b>Objective</b>:<br>
1. Create a house pricing prediction engine for the family<br>
2. Find 10 best house recommendation that meet the family's needs (budget \~\$25,000, 7 rooms, and secure from crime)

Written by: [ishaq101](https://github.com/Ishaq101)


### About Dataset

Housing Values in Suburbs of Boston
The `medv` variable is the target variable.
<br><br>

<b>Data description</b>
The Boston data frame has 506 rows and 14 columns.
<br><br>
This data frame contains the following columns:<br>
`crim` : per capita crime rate by town.<br>
`zn` : proportion of residential land zoned for lots over 25,000 sq.ft.<br>
`indus` : proportion of non-retail business acres per town.<br>
`chas` : Charles River dummy variable (= 1 if tract bounds river; 0 otherwise).<br>
`nox` : nitrogen oxides concentration (parts per 10 million).<br>
`rm` : average number of rooms per dwelling.<br>
`age` : proportion of owner-occupied units built prior to 1940.<br>
`dis` : weighted mean of distances to five Boston employment centres.<br>
`rad` : index of accessibility to radial highways.<br>
`tax` : full-value property-tax rate per \$10,000.<br>
`ptratio` : pupil-teacher ratio by town.<br>
`black` : 1000(Bk - 0.63)^2 where Bk is the proportion of blacks by town.<br>
`lstat` : lower status of the population (percent).<br>
`medv` : median value of owner-occupied homes in \$1000s.<br>


### Model Evaluation

metrics|lin_reg|sgd_reg|tre_reg|xgb_reg|rfo_reg|vot_reg
---|---|---|---|---|---|---
mae|3.411528|3.241945|2.680823|2.346198|2.353747|2.196802
mse|21.041489|19.522092|12.373920|10.161532|9.191053|8.735431
rmse|4.587100|4.418381|3.517658|3.187716|3.031675|2.955576
r2|0.725469|0.745293|0.838556|0.867421|0.880083|0.886028