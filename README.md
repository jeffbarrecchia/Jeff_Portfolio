# Introduction

Hello! My name is Jeff Barrecchia, and I am an aspiring Data Analyst. I am currently in my senior year at Rowan University, pursuing a Bachelor's Degree in Mathematics and a Minor in Economics. I am set to graduate in December of 2020, and as such have built out this portfolio to display my skills. Every project featured on this page, and on my GitHub, is strictly done in Python. Packages I used include, but are not limited to: pandas for dataframe and csv manipulation; numpy for advanced mathematical computations; scikit-learn for regression and/or classification done; and matplotlib/seaborn for visuals and plotting. Thanks for visiting my page!

# Projects Done via Python

## [Project 1: Building Fitness Profiles for Customers](https://github.com/jeffbarrecchia/Fitness_Profile_Project)
(click above for Fitness repo)

This project was done with a dataset pulled off of Kaggle. It features several different graphs and modeling as well as a couple simple linear regression examples to predict how many miles a customer will plan on riding per week. These are based off of several factors: income, gender, age, and current fitness level the customer says they are at.

![](/images/pairplot.png)

## [Project 2: Predicting Diabetics Through Classification](https://github.com/jeffbarrecchia/diabetic_classification)
(click above for Techniques repo)

In this code, I display several different Classification methods to predict who does or does not have diabetes. The dataset was pulled off of Github. The methods are:

  1. K-Nearest Neighbor
  2. Decision Tree Classification
  3. Random Forest Classification
  4. Support Vector Classification

![](/images/training_vs_test_accuracy.png)

## [Project 3: Predicting Boston House Prices Through Regression](https://github.com/jeffbarrecchia/Boston_Housing_Regression)
(click above for Housing Regression Repo)

This project used linear regression in order to determine the price of a house based off of several factors. These factors include but are not limited to:

  1. Crime Rate
  2. Rooms in the House
  3. Age of the House
  4. ...
  
![](/images/heatmap_boston_housin.png)

## [Project 4: Predicting Test Scores Through Regression](https://github.com/jeffbarrecchia/Test_Score_Regression)
(click above for GPA Regression Repo)

With this dataset, there were a few challenges, most namely dealing with the nominal variables and how to perform regression with those. I researched and came up with a technique in the pandas module: get_dummies. This added 26 new columns, but made the regression possible. The model achieved an accuracy of 83.09% on the training dataset, and an accuracy of 87.96% on the test dataset.

![](/images/distribution_of_grades.png)

# [Project 5: Predicting Marriage Through Classification](https://github.com/jeffbarrecchia/married_at_first_sight_classification)
(click above for Marriage Repo)

This dataset was pulled from Kaggle.

Married at First Sight is an A&E social experiment show, where people who sign up for the show are matched by sociologists and data analyts based on their compatibility. The first time they meet is on the altar the day of their wedding. They get married, go on a honeymoon, and then are together for the next eight weeks when they then have to decide whether or not they want to stay married or get divorced. What I attempted to do was use Classification to predict whether or not the couples would still be married today. I used the get_dummies extension from the pandas library to change all of the categorical variables into 0's and 1's so the classification would work, and since there was no test dataset given I had to use the train_test_split package from the sklearn module to divide up the data. I used three different classification methods, all of which are also from the sklearn module: DecisionTreeClassifier, RandomForestClassifier, and KNeighborsClassifier. While their training dataset accuracy varies between the three methods, their test dataset accuracy was relatively the same as they all tended to fall at 78.571% accuracy fairly frequently.

![](/images/swarmAgeToStatus.png)


