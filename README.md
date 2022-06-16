# E-commerce-Prediction

The data attributes include yearly amount spent, avg. session length, time on spent on e-commerce app, time on spent on e-commerce website and length of membership.

**Loading and Analyzing the Data set**

The Dataset used is the E-Commerce data by Google Data. The data was downloaded from the UCI Machine Learning Repository. Viewing the Data in a Data Frame would produce the table below:

**Data Preparation**
The Data is in a csv (comma separated values) format and the data is loaded using the pandas library in python to enable us view the data in a Data Frame (Table Format). In preparing the data for analysis the columns in the dataset were renamed to the appropriate feature names, this was done using the pandas column function.

**The Breakdown of the features in the Data Frame is as follows**

1. yearly amount spent - (numeric: from 0 to ∞)
2. avg. session length - (numeric: from 0 to ∞)
3. time on app - (numeric: from 0 to ∞)
4. time on website - (numeric: from 0 to ∞)
5. length of membership - (numeric: from 0 to ∞)

**Descriptive Statistics of the E-commerce dataset**

The count shows a total of 500 data rows for each set of variables with no missing values. The mean, standard deviation, minimum and maximum values are all on display in the figure above. The values at the 25th, 60th and 75th percent quartiles are also described in the figure 4.2.

**Correlation figures between the variables**

The correlation between the amount spent yearly and avg. session length, time spent on e-commerce app, time spent on e-commerce website and length of membership is 0.36, 0.5, -0.003 and 0.809 respectively. This suggests that there exists a positive weak correlation between amount spent yearly and avg. session length and time spent on e-commerce app, while there exists a negative weak or no relationship between amount spent yearly and time spent on e-commerce website but the relationship between amount spent yearly and length of membership was positive and very good.

**Model Discussion**

The model shows that a unit change in amount spent yearly will bring about 25.888 units change in avg. session length, also a 38.871 change in time spent on e-commerce app, while a 0.471 unit change in time spent on e-commerce website and 6.784 unit change in length of membership. Thus, this suggests that there will be a positive change in each feature(variable).
The R-square showed the coefficient of determination which is 0.986. This implies that 98.6% of the amount spent yearly is explained by avg. session length, time spent on e-commerce app, time spent on e-commerce website and length of membership while the remaining 1.4% is explained by other factors not considered in this hypothesis. This also suggest that the model is adequate to fit the variables in question.
