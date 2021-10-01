---
layout: page
title: Portfolio
permalink: /portfolio/
---

### Price transparency Texas hospitals (Python)
US hospitals are required to post their prices online, but hospitals are all over the map on formatting. The first goal was to find the files in their different websites, clean and transform the data, and upload it to a SQL database for analysis. This is a work in progress.

* Collect, clean, transform, and analyze data
* Python, Docker, Postrges SQL, Flyway

[Project link][txtrans]

---

### ULB credit card fraud prediction (Python)
This data set includes over 280,000 credit card transactions made in September 2013 by European cardholders.

The goal is to predict whether a transaction is fraudulent or not based on the 30 variables provided. Most of the variables are the principal components obtained with the PCA of the original data.

* Classification
* Logistic Regression, LDA, Random Forest, Gradient Boosting

[Project link][edscc]

---

### ULB credit card fraud prediction (R)
I did the ULB credit card fraud prediction project in R to practice and to compare implementation differences of R vs. Python.

* Classification
* Logistic Regression, SVM, Random Forest, Gradient Boosting

[Report in pdf][gitcc]  
[GitHub link][jQScc]

---

### Lending Club loans (Python)

This was my entry to the workspace competition at [Data Camp][dc]. The data set contains information for almost 10,000 loans issued by [Lending Club][lc]. 

There were multiple goals for this project: explore the data, visualize it, and try to extract useful insights. Estimate the time it takes users to pay back their loans and explore the different types of customers that take loans for different purposes.

As a final step, the goal was to build a model to predict whether a loan will be paid back in full. 

* Classification
* Logistic Regression, Random Forest, Gradient Boosting

[Project link][dcwc]

---

### UK used cars market (Python)

This was the project I presented to achieve Data Scientist Professional [certification][dspc] from [Data Camp][dc]. The data set contains price information for 6,700 used cars in the UK. 

The goal is to estimate the price of used cars within £1,500 using the 8 variables provided.

* Regression
* Regularized Regression, Random Forest, Gradient Boosting

[Project link][toyota]

---

### Budgeting Web App (Flask, Python, SQL)
A budgeting app where the user can track their expenses based on the envelopes method. It is inspired on a very good commercial application called [Goodbudget][gdbgt].

* JavaScript, Python, Flask, and SQL

[Project video][cs50bud]

---

### MovieLens movie recommendation system (R)
A movie recommendation system using the [MovieLens][movielens] data set.

This data set contains 10 million ratings of more than 10,000 movies given by about 70,000 users. This was a guided project where we were provided some of the code to set up the data set and we based the recommendation system on an example from the course series.

* Recommendation System
* Regularization

[Report in pdf][gitmovie]  
[GitHub link][jQSmovie]

---

### Data Camp projects (Python)
I have been taking many [Data Camp][dc] courses for the last 18 months. These are all the projects I have completed.

* Data Manipulation
* Data Visualization
* Importing and Cleaning Data
* Machine Learning

[Data Camp projects][dcproj]

---

### White wine & red wine (Python)
There are two data sets, one for white wine (4,898 wines) and one for red wine (1,599 wines). The goal is to create a model that estimates the subjective rating of a wine as graded by experts, using the physicochemical properties of the wine in the data set.

* Regression
* Regularized Regression, Random Forest, Gradient Boosting

[White wine link][white]  
[Red wine link][red]


[txtrans]: https://github.com/jQSfire125/price-transparency-tx
[edscc]: https://nbviewer.jupyter.org/github/jQSfire125/ULB-Credit-Card-Fraud/blob/main/Capstone-ULB-Credit-Card-Fraud.ipynb
[jQSmovie]: https://github.com/jQSfire125/MovieLens
[gitmovie]: https://github.com/jQSfire125/MovieLens/blob/master/report.pdf
[movielens]: https://grouplens.org/datasets/movielens/10m/
[jQScc]: https://github.com/jQSfire125/CreditCard
[gitcc]: https://github.com/jQSfire125/CreditCard/blob/master/report.pdf
[dc]: https://www.datacamp.com
[lc]: https://www.lendingclub.com
[dcwc]: https://app.datacamp.com/workspace/w/03e54e71-e0c8-450b-a2fd-6449232efdc1
[toyota]: https://nbviewer.jupyter.org/github/jQSfire125/Toyota/blob/main/toyota.ipynb
[dcproj]: https://github.com/jQSfire125/DataCamp-Projects
[white]: https://nbviewer.jupyter.org/github/jQSfire125/Wine/blob/main/Capstone-Wine-White.ipynb
[red]: https://nbviewer.jupyter.org/github/jQSfire125/Wine/blob/main/Capstone-Wine-Red.ipynb
[dspc]: https://www.datacamp.com/certificate/DS0019388936730
[cs50bud]: https://youtu.be/Vg3lJGAUAaU
[gdbgt]: https://goodbudget.com/