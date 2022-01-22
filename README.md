# Book-Recommendation-System
## Problem Statement-
In today’s world there are lots of books present. Users read books and give ratings and reviews according to their interest and experience.

In this project we will create a recommendation system which will provide genuine suggestion of the books to the user.
## Introduction-
Recommendation system is defined as the computer program that helps the user determine goods and content by predict the users rating of each item and presentation them the substance that they would rate highly. The recommendation system is containing three types that are: collaborative filtering, content based filtering and hybrid filtering.
## Objective-
Building a Book recommendation system which can suggest books matching with user’s interest.
## Methods Used
Descriptive Statistics
Data Visualization
Machine Learning
## Technologies-
Python
Pandas
Numpy
Matplotlib
Seaborn
Scikit-learn
Surprise
## Data-
The Book-Crossing dataset comprises 3 files.

Users : Contains the users. Note that user IDs (User-ID) have been anonymized and map to integers. Demographic data is provided (Location, Age) if available. Otherwise, these fields contain NULL values.

Books : Books are identified by their respective ISBN. Invalid ISBNs have already been removed from the dataset. Moreover, some content-based information is given (Book-Title, Book-Author, Year-Of-Publication, Publisher), obtained from Amazon Web Services. Note that in the case of several authors, only the first is provided. URLs linking to cover images are also given, appearing in three different flavors (Image-URL-S, Image-URL-M, Image-URL-L), i.e., small, medium, large. These URLs point to the Amazon website.

Ratings : Contains the book rating information. Ratings (Book-Rating) are either explicit, expressed on a scale from 1-10 (higher values denoting higher appreciation), or implicit, expressed by 0.
## Project Description-
EDA - Performed exploratory data analysis on numerical and categorical data.
Data Cleaning - Missing value imputation,Outlier Treaatment
Feature Selection - Used User-ID,ISBN and Books-Rating for model development.
Model development - Tried Popularity based model and Collaborative filtering (Both Memory based and Model based).
## Needs of this project-
data exploration
data processing/cleaning
recommendation system developer

