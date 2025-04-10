# Project: Recommendations with IBM

## Table of contents
1. [Project Motivation](#motivation)
2. [Installation](#installation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## 1. Project Motivation <a name="motivation"></a>
This project is part of the Data Scientist Nanodegree Program with Udacity. 

It is made in collaboration with IBM Watson Studio. The main goal is to analyze the interactions that users have with articles on their platform and to make recommendations to the users about articles that they might like. 

## 2. Installation <a name="installation"></a>

There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python.  The code should run with no issues using Python versions 3.*.

## 3. Files Descriptions <a name="File Descriptions"></a>
Here is an overview of the provided files: 

- data
| - articles_community.csv # data to process 

| - user-item-interactions.csv # data to process 

- README.md

- Recommendations_with_IBM.html #.html version of ipynb file 

- Recommendations_with_IBM.ipynb # Notebook contaning the solutions for the project´s questions

- project_tests.py # .py file with solutions to match the notebook

- top_10.py # top 10 articles

- top_20.p  # top 20 articles

- top_5.p # top 5 articles

- user_item_matrix.zip # user_item_matrix.p zipped - please unzip to use.

## 4. Results <a name="results"></a>
The project requires to go through: 
  1. Exploratory Data Analysis
  2. Rank Based Recommendations
  3. User-User Based Collaborative Filtering
  4. Matrix Factorization
After going through the process, we can conclude that the SVD model showed overfitting, with training accuracy increasing and test accuracy decreasing, as the number of latent features grew - likely due to a small number of common users. To improve the recommendation, we could reduce the number of latent features and evaluate performance through A/B testing and continue collecting feedback from the users.

## 5. Licensing, Authors, and Acknowledgements <a name="licensing"></a>

Thank you IBM Watson Studio for providing the datasets. The datasets used in this project are licensed under the [Creative Commons Attribution-NonCommercial 4.0 International License (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/). This allows for the use of the data for non-commercial purposes, provided that appropriate credit is given, a link to the license is included, and any changes made are indicated.

Thank you [Udacity](https://www.udacity.com/) for training materials, the fantastic support from the mentors on the Knowledge Base, as well as Udacity´s AI. All tools provided by Udacity were extremely helpful. 
