# Photos-App-users-Insight

This is an example of Exploratory Data Analysis (EDA) and some modeling . 
## Problem Statement

Photos team is interested in understanding their user base. To help explore this question,
we have provided a sample dataset* of Photos App users. The dataset includes their feature 
usage as well as related information about the user and their device. All usage activity
in the dataset is aggregated over a month for each user.
We would like for you to use this data to help the team understand the different types of 
Photos app users and insights about the user segments that were found.

### Objective of Analysis

* Understanding Numerical and categorical variables 
* Understanding General userers feature usage, special users and heavy users
* Finding similarities between product features by usage
* Finding clusters between users
* Is it possible to predict a new user's future behavior from their initial information ?

### Contents of Analysis

* Priliminary  Exploratory Data Analysis (EDA)
    * Import required modules and load data
    * Just making sure uniqueness of primery key
    * Checking for missing values
    * Let's analyse Categorical features
    * Modifying CountryShortName
    * Modifying MostUsedPhotoApps
    * Let's check Numerical variables
* Features usage by Users category
    * Features usage by all users
    * Special or Advanced features/users
    * Heavy Users/Outliers
    * Are outliers and special users are same ? Or what is the intersection ?
* Similarity between features
    * Content based similarity for special features based on product usage
    * Content Similarity for all numeric features
    * Factor Analysis to see if we can get some insights about factors
    * User based similarity using KNN
* Clustering and prediction for new users
    * How is the behavior of Outliers or Special Users different then general users ?
    * Is it possible to predict General or Special category before users start using product?
    * Try cluster for all users
    * PCA followed by K-means clustering
    * Cluster using Gaussian Mixture
    * Classification model where target values are GMM clusters
    * How the target values are different for numerical variables
    * Let's see categorical variables with target
    * Let's try building models
* Conclusion 
