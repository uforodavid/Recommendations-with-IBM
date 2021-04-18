# Recommendations-with-IBM


### Table of Contents
1. [Introduction](#intro)
2. [Installation](#installation)
3. [Tasks](#task)

## Introduction <a name="intro"></a>
For this project I analyzed the interactions that users have with articles on the IBM Watson Studio platform, and made recommendations to them about new articles they may like. Below we can see an example of what the dashboard could look like displaying articles on the IBM Watson Platform.
![image1](ibm.png)


## Installation <a name="installation"></a>
Installation of Python 3, Numpy, Pandas Matplotlib, and pickle.


## Tasks <a name="task"></a>
I. Exploratory Data Analysis
Before making recommendations of any kind, we need to explore the data we are working with for the project.

II. Rank Based Recommendations
To get started, we will first find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering
In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users. You will implement this next.

IV. Matrix Factorization
Finally, we will complete a machine learning approach to building recommendations. Using the user-item interactions, we will build out a matrix decomposition. Using your decomposition, we will get an idea of how well you can predict new articles an individual might interact with. We will finally discuss which methods you might use moving forward, and how you might test how well your recommendations are working for engaging users.



