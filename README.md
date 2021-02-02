# Seattle Airbnb Analysis

### Table of Contents

1. [Installation and Libraries](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation and Libraries  <a name="installation"></a>

You will need the standard data science libraries found in the Anaconda distribution of Python 3.6:

- numpy                 `import numpy as np`
- pandas                `import pandas as pd`
- matplotlib.pyplot     `import matplotlib.pyplot as plt`
- seaborn               `import seaborn as sns`

## Project Motivation<a name="motivation"></a>

For this project, I was interested in using Airbnb [Seattle Open Data from Kaggle](https://www.kaggle.com/airbnb/seattle) from Jan 2016 to Jan 2017 to answer following questions:

1.	Which kind of accommodations are listed where and how do they make up the price?
2.	How is the price progress over the year?
3.	What time of year is the most popular for bookings?
4.	Which Neighborhood is the most popular?
5.	Which of the Seattle’s Top 10 neighbourhoods are the most expensive?
6.	What are the most mentioned words in the comments?
7.	Which type of accommodation has the most reviews?
8.	Which hosts have had the highest availability in the given period?
9.	Which hosts have the highest estimated revenue, assuming that availability has been fully used?


## File Descriptions <a name="files"></a>
Repository structure:

    SeattleAirBnB_Analysis/                  # folder
    ├── README.md                            # read.me file 
    ├── listings.csv                         # data set sistings
    ├── reviews.csv                          # data set reviews
    ├── calendar.csv                         # data set calendar
    ├── Prj1_Seattle-Airbnb_Analysis.ipynb   # Jupyter notebook with the analysis
    
There is 1 jupyter notebook available here to show the analysis related to the above questions. Markdown cells and comments were used to assist in walking through the steps.  

The 3 csv files used for the analysis are downloaded from [kaggle](https://www.kaggle.com/airbnb/seattle).

## Results<a name="results"></a>

The main findings of the analysis can be found in the Blog Post available [here](https://selen-gerel.medium.com/9-insights-about-seattles-airbnb-ec6832df64f).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Appreciative big thanks to Airbnb for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/airbnb/seattle).
