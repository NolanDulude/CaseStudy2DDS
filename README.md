# CaseStudy2

Helllo, my name is Nolan Dulude and for this project I was tasked with trying to determine Attrition from a dataset that was provided by HR.  Within this code you will find an exploritory analysis using graphs to get a visualization of Attrition along with Monhtly Income, Age, Job Role, Stock Option Level, and Overtime.  I decided based on the intial graphs that I would like to explore the Job Role, Stock Option Level, and Overtime furhter.  This further exploration included a KNN model for determining Attrition with using Job Role, Stock Option Level, and Overtime as my variables.  The goal of this model was to have a Sensitivity and Specificity greater than 0.6, which was achieved by changing the threshold vaules. I achieved a better Specificity of 0.7273 and Sensitivity of 0.6829 with respect to the No attritions. Also, a Specificity of 0.6829 and Sensitivity of 0.7273 with respect to the Yes Attritions.  My K value for both was 5.  The mean F1 score was 0.606.  Within this code you will aslo find a Multiple Regression model for determing the Monthly Income of empolyees.  For this model I used Total Working Years and Age to determine the Monthly income with a RMSE value of <3000, this Model gave me a RMSE of 2891 and an R² of 0.607.  There are two csv files that have been export from the code that have predicted the Attrition and Monthly income.  These are named Case2PredictionsDulude Attrition.csv and Case2PredictionsDulude Salary.  I have also provided my R Shiny App that can be used to show the relationship between Attrtion and some of the variables provided through histogram and scatter plots.  
