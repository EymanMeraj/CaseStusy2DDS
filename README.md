# CaseStusy2DDS
Executive Summary for DDS Project 2
Link to github website: https://eymanmeraj.github.io/
Link to Presentation: https://github.com/EymanMeraj/CaseStusy2DDS/blob/main/Presentation.mp4

We employed a comprehensive analysis, delving into over 30 variables that potentially influence employee attrition within Frito Lay Corporation. Our focus was on understanding the nuanced interplay between these variables and the propensity for attrition among the workforce.

Employee attrition, a critical concern for any organization, is often linked to myriad factors – from job satisfaction and growth opportunities to work environment and compensation. Recognizing the substantial investment companies make in recruiting, training, and nurturing talent, we aimed to uncover actionable insights that can stem attrition and fortify Frito Lay's employee retention strategies.

Our initial investigation centered on visually assessing the impact of these variables on attrition levels. This approach provided valuable insights into the correlations and potential trends, setting the stage for a deeper dive into the data to unearth predictive patterns.

From the boxplots and the summary table of means, noticeable disparities emerge in the distributions and means of "StockOptionLevel," "YearsInCurrentRole," "YearsWithCurrManager," "TotalWorkingYears," and "MonthlyIncome" when grouped by attrition status. Indicating those 5 variables may be the key factors that cause "Attrition". 
Based on the p-values and the contingency tables, we see that there are higher proportions of attrition among people with overtime and those who work as sales representatives. Thus, the variable "OverTime" and "JobRole" are highly related with attrition.

 The Top 3 Factors would be "StockOptionLevel," "YearsInCurrentRole," and "OverTime"

We Build two models:
for Naive Bayes model we use the top 11 numerical variables which have a relative difference at least 10%, and 5 categorical variables that has a p-value less than 0.01.
and for KNN model we use the top 11 numerical variables which have a relative difference at least 10%.

for the Naive Bayes model the accuracy was %82, sensitivity of %85 and Specificity of %63
for the KNN model model the accuracy was %89, sensitivity of %93 and Specificity of %65

