# MSAN 601 - Linear Regression Analysis

## James D. Wilson

**Email**: jdwilson4@usfca.edu

**Time Line**: Wednesday, August 22nd - Wednesday, October 11th

**Class Time**: M, W: 10:00 - 11:50 AM; 1:15 - 3:05 PM in Howard Room 527

**Office Hours**: M, W: 3:30 - 4:30 PM in Howard 5th floor Agora 

**Grader**: Anshika Srivastava (asrivastava3@dons.usfca.edu)


## Textbooks

- *Applied Linear Regression Models- 4th Edition* by Kutner, Nachtsheim, and Neter (Required)
- *Introduction to Statistical Learning* ([online](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf))
- *Elements of Statistical Learning* ([online](https://web.stanford.edu/~hastie/Papers/ESLII.pdf))
- *Linear Models with R* by Julian Faraway
- *Statistical Inference* by Casella and Berger

## Course Learning Outcomes

By the end of this course, you will be able to

- Formulate and apply classical simple and multiple linear regression models
- Formulate and test hypotheses and use models for both prediction and explanation
- Use R to load and manipulate data, fit regression models, and generate various outputs like ANOVA tables, confidence intervals for parameters, and diagnostic assessments
- Verify/test whether or not fitted residuals conform to the assumptions that underlie classical regression
- Identify and manage outliers and influential observations
- Assess and address multicollinearity, heteroscedasticity, autocorrelation, non-normality, model misspecification
- Communicate the results of complete and well-reasoned regression analysis


## Course Overview


The focus of this course will be to provide you with the basic mathematical and computational techniques available for making informed, data-driven decisions using regression models. We will implement the models using the R programming language. We will discuss the following topics

- Distributional Theory: the Normal, t, Chi-Squared, and F distributions
- Statistical Inference: estimation, hypothesis tests, and confidence intervals
- Simple and Multiple Linear Regression
- Model Building and Variable Selection
- Outlier detection
- Model Diagnostics: outliers, multicollinearity, non-normality, autocorrelation
- Analysis of Variance (ANOVA)
- Logistic Regression
- Shrinkage Methods: the Lasso and Ridge Regression


### Assessment

The focus of this course will be to provide you with the basic techniques available for making informed, data-driven decisions using the R programming language. This is *not* a statistics course, but will provide you the intuition to make hypotheses about complex questions through visualization, wrangling, manipulation, and exploration of data. The course will be graded based on the following components:

- **Assignments** (30%): You will be assigned computational and theoretical homework assignments to be completed and turned in on Canvas
- **Quizzes** (20%): Each week you will be given a short quiz that tests the main lessons taught in class from the previous week. These are given on **Mondays at 9:00 AM**
- **Final Exam** (30%): The final exam will be a comprehensive exam covering the main components of Regression analysis
- **Final Project** (20%): The final project will be a computational case study that brings together the techniques learned throughout the semester. The description for this project will be provided towards the mid point of the semester.

### Quizzes

- 8/28/17: [Quiz 1](https://github.com/jdwilson4/Regression-Analysis/blob/master/Quizzes/Quiz1.pdf)
- 9/6/17: [Quiz 2](https://github.com/jdwilson4/Regression-Analysis/blob/master/Quizzes/Quiz2.pdf)
- 9/18/17: [Quiz 3](https://github.com/jdwilson4/Regression-Analysis/blob/master/Quizzes/Quiz3.pdf)
- 9/27/17: [Quiz 4](https://github.com/jdwilson4/Regression-Analysis/blob/master/Quizzes/Quiz4.pdf)

### Homework

- [Homework 1](https://github.com/jdwilson4/Regression-Analysis/blob/master/Homework/Homework1.pdf). Due Thursday, September 7th at 9:00 AM on Canvas
- [Homework 2](https://github.com/jdwilson4/Regression-Analysis/blob/master/Homework/Homework2.pdf). Due Thursday, September 21st at 9:00 AM on Canvas
- [Homework 3](https://github.com/jdwilson4/Regression-Analysis/blob/master/Homework/Homework3.pdf). Due Wednesday, October 11th at 5:00 PM on Canvas

### Final Case Study
- [Case Study](https://github.com/jdwilson4/Regression-Analysis/blob/master/Case%20Study/Case_Study.pdf). Due Friday, 10/6 at 9:00 AM. [[Data]](https://github.com/jdwilson4/Regression-Analysis/blob/master/Case%20Study/housing.txt); [[Data Description]](https://github.com/jdwilson4/Regression-Analysis/blob/master/Case%20Study/Data_Description.txt); [[Morty House]](https://github.com/jdwilson4/Regression-Analysis/blob/master/Case%20Study/Morty.txt)

### Schedule

<!-- **Completed Assignments:** [Submit](https://www.dropbox.com/request/mShmGgweXQGIhWxa1Xma) -->

**Introduction and Motivation** 

| Topic | Reading | Practice | In-Class Code |
|:--- | :---  | :---  |  :--- |
|[Intro and A Brief History of Data Science](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Lecture%201%20Introduction.pdf)| [Ch. 1 of *Doing Data Science*](https://www.safaribooksonline.com/library/view/doing-data-science/9781449363871/ch01.html) | Read [this](https://github.com/jdwilson4/Regression-Analysis/blob/master/Papers/Explain%20or%20Predict.pdf)| |
| [Overview of Machine Learning](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Intro_Machine_Learning.pdf) | [Ch. 1 of ISL](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf) | | |
| [Model Building from the Statistical Learning Perspective](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Lecture%202%20Intro%20to%20Statistical%20Modeling.pdf) | [Ch. 2 of ISL](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Lecture%202%20Intro%20to%20Statistical%20Modeling.pdf)| | |


**Model Fitting and Inference**

| Topic | Reading | Practice | In-Class Code |
|:--- | :---  | :---  |  :--- |
| [Simple Linear Regression: Model and Estimation](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Least_Squares_Estimation.pdf) | [Ch. 3 of ISL](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf)| [Ch 3.6.1 - 3.6.3 ISL](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf)| [Intro to Regression in R](https://github.com/jdwilson4/Regression-Analysis/blob/master/Code/Regression_Tutorial.pdf)|
| Basics of Statistical Inference | | | |
| [Tests, Confidence Intervals, and Prediction Intervals](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/CI_Notes.pdf)| [Ch 2 and 3 of Linear Models with R](http://www.utstat.toronto.edu/~brunner/books/LinearModelsWithR.pdf)| | |
| [Shrinkage Methods - Ridge and Lasso](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Lecture%203%20Shrinkage%20Methods.pdf) | [Ch. 6 of ISL](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf)| | [Penalized Regression in R](https://github.com/jdwilson4/Regression-Analysis/blob/master/Code/Shrinkage.pdf)|



**Model Diagnostics**

| Topic | Reading | Practice | In-Class Code |
|:--- | :---  | :---  |  :--- |
| [Influential Points and Outliers](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Influential_Points.pdf) | [Ch 4.2 of Linear Models with R](http://www.utstat.toronto.edu/~brunner/books/LinearModelsWithR.pdf) | | |
| [Tests of Normality and Equal Variance](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Normality_Variance.pdf)| [Ch 4.1, 4.3 of Linear Models with R](http://www.utstat.toronto.edu/~brunner/books/LinearModelsWithR.pdf) | | |
| [Collinearity](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Collinearity.pdf) | [Ch 5.3 of Linear Models with R](http://www.utstat.toronto.edu/~brunner/books/LinearModelsWithR.pdf)| | |
| [Transformations](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Transformations.pdf) | [Ch 7 of Linear Models with R](http://www.utstat.toronto.edu/~brunner/books/LinearModelsWithR.pdf)| | |


**Generalized Linear Models**

| Topic | Reading | Practice | In-Class Code |
|:--- | :---  | :---  |  :--- |
| [Classification and Logistic Regression](https://github.com/jdwilson4/Regression-Analysis/blob/master/Lectures/Logistic%20Regression.pdf) | | [Ch. 4.3 of ISL](http://www-bcf.usc.edu/~gareth/ISL/ISLR%20First%20Printing.pdf)| | 



### Additional Resources
- [Base R Cheat Sheet](https://www.rstudio.com/wp-content/uploads/2016/10/r-cheat-sheet-3.pdf)
- [Try R by CodeSchool](http://tryr.codeschool.com/) Quick, interactive R coding lessons
- [Swirl](http://swirlstats.com/students.html) (skip step 1 and 2 if you have already installed R and R Studio) Interactive coding lessions in R Studio

### Important Dates

- Wednesday, August 23rd - First day of class
- Monday, September 4th - Labor Day Holiday, **no class**
- Wednesday, October 11th - Last day of class
