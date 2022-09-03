
# Play Store App Review Analysis



The objective of this project to performed exploratory data analysis to discover key factors responsible for app engagement and success.


## Problem Statement
The objective of this project to performed exploratory data analysis to discover key factors responsible for app engagement and success.

## Data provided by :
AlmaBetter

## Data Description

## Description

## 1. Play Store App Data

It consists of 13 columns with 10841 Rows:

1.App: Name of the App

2.Category: Category under which it falls

3.Rating: Application’s rating on playstore

4.Reviews: Number of reviews of the app

5.Size: Size of the app

6.Installs: Number of Installation of the app

7.Type: Whether the app is free or paid

8.Price: Price of the app if it’s a paid app (0 if it’s a free app)

9.Content Rating: Appropriate target audience of the app

10.Genres: Genres under which the app falls

11.Last Updated: Date when the App was last updated

12.Current Ver: Current version of the App

13.Android Ver.: Minimum android version required to support the App

## 2. User Reviews Data

In this data set the review given by the consumers were calculated on different parameters, as:

1.App

2.Translated review

3.Sentiment

4.Sentiment Polarity

5.Sentiment Subjectivity

Asking Questions from Dataset
1.	What is the top 5 apps on the basis of installs?
2.	What is the top 5 reviewed apps?
3.	What is the top 5 expensive apps?
4.	What is the top 3 most installed apps in Game category?
5.	Which 5 apps from the category are having the lowest rating?

## Preprocessing

1)Importing libraries

2)Loading data frame

3)Internal research of data i.e. type , shape, duplicate values, missing values.

4)dropping duplicate values

5)cleaning the data : 

•	Removing visual impurities like sign.

•	Comparing unique and non null values to check how many entries were repeated.

•	Filtering null values by operating on each column individually.

6)Data visualization :

We plotted following graphs

●	Distribution of Application Type

●	Number of Apps per Category

●	Number of installs type-wise according to categories

●	Top genres in playstore

●	Number of installs for each category

●	Number of apps per category differentiated by type

●	Distribution of Size of app

●	Impact of size on the number of installs

●	Distribution of App Rating

●	Install per Rating

●	Distribution of Apps in terms of their Ratings, Size and Type

●	Reviews Sentiment

●	Distribution of type of reviews as per categories

●	Distribution of Subjectivity

●	Sentiment subjectivity and Sentiment Polarity

●	Content Rating on the basis of Age

●	Sentiment polarity relation with type of app

●	Content Rating relation with Sentiment Polarity

●	Categories Relation with Sentiment Subjectivity

## Conclusion from Analysis

•	Most of the trending apps are from the categories like family, tools, and games.

•	Most preferred Apps by users in point of size or weight are light size apps.

•	Users also installed apps on the basis of their ratings.

•	These ratings are defined on 2 points- Polarity and Subjectivity

•	This analysis will help developers while preparing for their next apps.
