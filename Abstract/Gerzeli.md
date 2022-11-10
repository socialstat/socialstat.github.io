University student retention is one of the most challenging problems that affects academic institutions.
The aim of this paper is to identify the best machine learning method to identify in advance the university students who are at risk of dropping out.
This can lead to the development of effective strategies of dropout prevention. The prediction models are based on a real dataset provided by the University of Pavia which includes 4,574 students enrolled in the first year of all the courses offered by the University of Pavia. The predicted probabilities are exploited to stratify students and to identify the most at risk students.
The information available in the dataset is: demographics (age, sex, residential code, nationality), educational background (high school score, high school graduation year, type of high school), enrolment related information (type of enrolment to the course, age of enrolment, debits derived from enrolment test), information about tax payment, department and course. Information about participation to orientation events before the enrolment has also been added to the classical input variables used for the prediction of freshmen attrition.
The models under comparison are: Naive Bayes (NB), Logistic Regression (LOGR), Support Vector Machine (SVM), Decision Tree (DT), Random Forest (RF), AdaBoost (ADABOOST), Linear Mixed Model (MIXED).
The results obtained are quite good, but there is no outstanding model both in terms of accuracy and AUCs. The higher performances are reached by Logistic Regression and AdaBoost.

 		
