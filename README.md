The project is on Predicting the Popularity of Online News using Machine learning.

The data set is downloaded from, https://archive.ics.uci.edu/ml/datasets/online+news+popularity

The ‘Mashable’ news article dataset from UCI Machine  Learning Repository is used for the analysis. The goal is to predict the popularity of online news in social media using Machine learning.
The data set is summarizes the heterogeneous set of features about the article published by Mashable in period of two year, from 7-jan-2013 to 7-jan-2015.
  
 About Mashable: Mashable is a digital media website founded in 2005 for news and blogging. As of November 2015, it has over 6,000,000 twitter follower and over 3,200,000 fans on Facebook. 

The dataset contains 61 features (60 attribute & 1 target variable) and 39797 Observations. 
I grouped them in the following categories: 
 1.   Dependent Variable: Number of shares of an article.
 2.   Document related: Internal and external links, contains videos/images, number of words, topic modelling with LDA, sentiment analysis
 3.   Channel Type: Entertainment, Lifestyle, Business, Social media, Technology.
 4.   Publish date: Weekdays, days passed since the publishing date

The other details of the all the variable given in report.

With these categories, we have 60 features to visualize and analyse the relationship with the number of shares (dependent variable). We can create two ML problems with this dataset:
1.	Regression: Predict the number of shares.
2.	Classification: Will the article be popular?
We define ‘popularity’ by establishing a minimum threshold to the number of shares. For this example: if the number of shares is above the median, it is Popular otherwise Unpopular.
Using the median as threshold helps with the balance of the dependent variable for the classification project.

1)    Data preprocessing and Data cleaning:

In this I checked outlier, missing values, detect and correct the inconsistant and inappropriate data.

2)    Exploratory Data analysis

I did EDA to explore imp feature of data. Plotted frequency distribution, graphs. Used the step wise regression model to select the best variables from 61 features.

3) Machine learning algorithm:

The goal is to predict the popularity of articles. So I implemented the regression to predict the number of shares and classification to predict whether the article is popular or not.

4) Model Evalution:

I found that the classifier Random forest and KNN gives the good accuracy as compare to other classifier.





 
