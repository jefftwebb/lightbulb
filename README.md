# lightbulb
Lightbulb is an R package featuring a collection of data analysis tutorials. The tutorials support learning in Introduction to Business Analytics and Statistics and Predictive Analytics, offered in the David Eccles School of Business at the University of Utah.

1.	Probability
2.	Comparing Means
3.	Simple Linear Regression
4.	Multiple Linear Regression
5.	Real World Regression
6.	Classification with Logistic Regression
7. The Bootstrap

To install lightbulb:
1.	Install two R packages on your computer, learnr and devtools: install.packages("devtools", "learner").
2.	Load the devtools package: library(devtools).
3.	Install the lightbulb package from this github repo: install_github("jefftwebb/lightbulb").

To use the lightbulb tutorials:
1.	Load the learnr package: library(learnr)
2.	Open a lightbulb tutorial using the run_tutorial() function in learnr. For example: run_tutorial("Probability", package = "lightbulb"). This will automatically bring up a browser window with the tutorial on probability.

