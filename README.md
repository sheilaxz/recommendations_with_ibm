

# Recommendations Algorithms with IBM Dataset  

The purpose of this project is to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they might like.



## Table of Contents

1. [Introduction](#intro)  
2. [Installation](#install)
2. [Recommendation Algorithms](#algorithm)  
3. [File Description](#files)  
4. [Licensing, Authors, and Acknowledgements](#licensing)


## 1. Introduction  <a name="intro"></a>

This project aims to analyze the interactions that users have with articles on the IBM Watson Studio platform, and make recommendations to them about new articles they might like. 

<br>
<img src="link" width="250" height="200">
<br>
<br>

The figure above is an example of what the dashboard could look like displaying articles (here newest articles are desplayed) on the IBM Watson Platform. For recommendations, similar board can be available that shows the articles that are most pertinent to a specific user.

In order to determine which articles to show to each user, a study of the data available on the IBM Watson Studio platform is performed, and several different recommendation algorithms are presented. 


## 2. Installation <a name="install"></a>

The libraries used in this analysis process include:
pandas, numpy, matplotlib.pyplot, re, nltk, sklearn, and pickle.

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. The code should run with no issues using Python versions 3.\*.


## 2. Recommendation Algorithms <a name="algorithm"></a>

Various recommendation algorithms shown in this project include:

- Rank Based Recommendations
- User-User Based Collaborative Filtering
- Content Based Recommendations
- Matrix Factorization


## 3. File Description <a name="files"></a>

### Datasets

There are two raw datasets used for model training and testing: 

- article_community.csv: A dataset about the articles and their information, such as article title, brief description, etc.  

- user_item_interactions.csv: A dataset recording users' interactions with articles, i.e., what article an user access to read.

The datasets can be found in folder [data](https://github.com/sheilaxz/recommendations_with_ibm/tree/main/data).


### Data Processing

"Recommendations_with_IBM.ipynb" is a Jupyter Notebook file showing how the raw training dataset is processed and how different recommendation algorithms are trained in this project. 

"top_5.p," "top_10.p," and "top_20.p" are pickle files used for algorithm testing in the jupyter notebook. "user_item_matrix.p" is a processed user-article matrix saved as pickle file. "project_tests.py" includes test functions used in jupyter notebook. These file is provided by Udacity Data Science NanoDegree. 


## 4. Licensing, Authors, and Acknowledgements <a name="licensing"></a>

Must give credits to: 
- IBM, who kindly provides the raw datasets, and 
- Udacity, who provides the nanodegree project, related materials, and the project


