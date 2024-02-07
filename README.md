# Analysis of Seattle Airbnb data
## Tips for would be hosts

This repository contains data from Seattle Airbnb in the form of CSV files and a Jupyter notebook for analysing, processing and visualising the data

I have also created a blog post to summarise the findings for non-technical people:
https://medium.com/@paul.c.shepherd/thinking-of-renting-your-property-using-airbnb-lets-see-what-renters-are-looking-for-a09d9a45f89c

## Libraries used

For data analysis I have used the [NumPy](https://numpy.org/) and [Pandas](https://pandas.pydata.org/) libraries
For data visualisation I have used the [Seaborn](https://seaborn.pydata.org/), [Matplotlib](https://matplotlib.org/) and [WordCloud](https://amueller.github.io/word_cloud/) libraries

## Project motivation

I have created this project as part of a [nanodegree](https://www.udacity.com/blog/2016/07/nanodegree-101.html) course from [Udacity](https://www.udacity.com/)
I was motivated to take the course as I find data science a fascinating subject and I'm very keen to increase my own knowledge on the subject, both for professional and private reasons

## File descriptions

- README.md: This file
- listings.csv: Airbnb dataset containing details about each property on the market in Seattle in April 2016
- reviews.csv: Airbnb dataset containing reviews of the same properties
- adjectives.csv: A list of 4800 English adjectives
- adjectives_scored.csv: The same list of adjectives but with scores assigned based on their appearance in scored reviews
- seattle_airbnb.ipynb: The Jupyter notebook used for all of the data processing and visualisation

## Using this project

You first must have all of the libraries mentioned above installed on your machine as well as software that supports the use of Jupyter notebooks
The project is set up so that the first cell must be run first, this loads all of the libraries and datasets. Once the first cell is run, the cells below may be run in any order depending upon your own preferences
The cell that scores the adjectives takes a long time to run, because of this, I have saved the results to another CSV file (adjectives_scored.csv) and this file is loaded on cells further down the notebook so that you can avoid running the adjective scoring cell (Unless you really want to!)

## Acknowledgements

Author: Paul Shepherd

Acknowledgements: Thanks to Udacity and the Data Scince course which has taught me many of the techniques used in analysing this data

Datasets
- [Seattle Airbnb](https://www.kaggle.com/airbnb/seattle/data)
- [English adjectives](https://patternbasedwriting.com/elementary_writing_success/list-4800-adjectives/)
