Question 1 
A medical research team wants to investigate the survival time of patients that have a particular type of liver
operation as part of their treatment. For each patient in the study, the following variables were recorded:
blood- Blood clotting Index
prognosis- Prognosis Index
enzyme- Enzyme function Index
liver- Liver function Index
age- Age of the patient, in years
gender- Gender of the patient, (Male of Female)
survival- Survival time of the patient after surgery (in days)
The data is available in the file surg.dat on iLearn.
a. Produce a scatterplot of the data and comment on the features of the data and possible relationships
between the response and predictors and relationships between the predictors themselves.
• You will need to remove the gender variable to do this.
• Comment on why it is necessary to remove the gender variable to compute the correlation matrix.
b. Compute the correlation matrix of the dataset and comment.
c. Fit a model using all the predictors to explain the survival response. Conduct an F-test for the overall
regression i.e. is there any relationship between the response and the predictors. In your answer:
• Write down the mathematical multiple regression model for this situation, defining all appropriate
parameters.
• Write down the Hypotheses for the Overall ANOVA test of multiple regression.
• Produce an ANOVA table for the overall multiple regression model (One combined regression SS
source is sufficient).
• Compute the F statistic for this test.
• State the Null distribution.
• Compute the P-Value
• State your conclusion (both statistical conclusion and contextual conclusion).
d. Using model selection procedures discussed in the course, find the best multiple regression model that
explains the data.
e. Validate your final model and comment why it is not appropriate to use the multiple regression model
to explain the survival time.
f. Re-fit the model using log(survival) as the new response variable. In your answer,
• Use the model selection procedure discussed in the course starting with log(survival) as the
response and start with all the predictors.
g. Validate your final model with the log(survival) response. In particular, in your answer,
• Explain why the regression model with log(survival) response variable is superior to the model
with the survival response variable
4
Question 2 [17 marks]
A car manufacturer wants to study the fuel efficiency of a new car engine. It wishes to account for any
differences between the driver and production variation. The manufacturer randomly selects 5 cars from the
production line and recruits 4 different test drivers.
kmL- The observed efficiency of the car in km/L over a standard course
car- The specific car (labelled 1, 2, 3, 4 or 5)
driver- The driver of the car (labelled A, B, C, D)
a. For this study, is the design balanced or unbalanced? Explain why.
b. Construct two different preliminary graphs that investigate different features of the data and comment.
c. Analyse the data, stating null and alternative hypothesis for each test, and check assumptions.
d. State your conclusions about the effect of driver and car on the efficiency kmL. These conclusions are
only required to be at the qualitative level and can be based off the outcomes of the hypothesis tests in
c. and the preliminary plots in b.. You do not need to statistically examine the multiple comparisons
between contrasts and interactions.