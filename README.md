# Recommendations with IBM Project (Udacity - Data Scientist Nanodegree Program)

## Table of Contents
1. [Introduction](#introduction)
2. [Project Overview](#project-overview)
	* [I. Exploratory Data Analysis (EDA)](#exploratory)
	* [II. Rank-Based Recommendations](#rank-based)
	* [III. User-User Based Collaborative Filtering](#user-user)
	* [IV. Content-Based Recommendations](#content-based)
	* [V. Matrix Factorization](#matrix-factorization)
3. [File Descriptions](#file-descriptions)
4. [Installation](#installation)
5. [Usage](#usage)
6. [License](#license)
7. [Acknowledgements](#acknowledgements)

## Introduction
This project is a part of Udacity's Data Scientist Nanodegree Program in collaboration with IBM. The aim is to analyze user interactions with articles on the IBM Watson Studio platform and develop a recommendation system to suggest new articles to users.

## Project Overview
The project is structured into the following tasks:

<a name="exploratory"></a>

### I. Exploratory Data Analysis (EDA)
We begin with an exploratory data analysis to understand the dataset and extract initial insights. This step is crucial for identifying patterns and preparing the data for the recommendation algorithms.

<a name="rank-based"></a>

### II. Rank-Based Recommendations
We create a simple recommendation system based on article popularity, measured by the number of user interactions. This approach helps in recommending the most popular articles to new users.

<a name="user-user"></a>

### III. User-User Based Collaborative Filtering
By identifying users with similar interaction patterns, we implement a collaborative filtering algorithm to recommend articles liked by similar users, thereby providing more personalized recommendations.

<a name="content-based"></a>

### IV. Content-Based Recommendations
Using natural language processing (NLP) techniques, we explore methods to recommend articles based on their content. This task, while optional, aims to enhance the recommendation system by utilizing article metadata and text.

<a name="matrix-factorization"></a>

### V. Matrix Factorization
We employ matrix decomposition techniques like Singular Value Decomposition (SVD) to predict user-article interactions. This machine learning approach helps in making more accurate recommendations based on user interaction patterns.

## File Descriptions
- **Recommendations_with_IBM.ipynb:** Jupyter Notebook containing the implementation of the project.
- **Recommendations_with_IBM.html:** HTML format of the project notebook.
- **top_10.p, top_20.p, top_5.p:** Pickle files containing the top 10, 20, and 5 articles respectively.
- **user_item_matrix.zip:** Zipped file containing `user_item_matrix.p`, the user-item interaction matrix used for SVD.

### Data Folder
- **articles_community.csv**: CSV file with details about the articles available on the IBM platform.
- **user-item-interactions.csv**: CSV file listing user interactions with the articles.

## Installation
To run this project, you need Python 3.5 or higher. The required libraries are included in the Anaconda distribution:
- pandas
- numpy
- matplotlib
- pickle

## Usage
1. Clone this repository to your local machine.
2. Unzip `user_item_matrix.zip` to extract `user_item_matrix.p`.
3. Open and run `Recommendations_with_IBM.ipynb` in Jupyter Notebook to execute the project.

## License

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)


## Acknowledgements
- [Udacity](https://www.udacity.com/) for the comprehensive Data Scientist Nanodegree program.
- [IBM](https://www.ibm.com/) for providing the user interaction dataset from IBM Watson Studio.
