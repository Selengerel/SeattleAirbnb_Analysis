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
- missingno             `import missingno as msno`

## Project Motivation<a name="motivation"></a>

For this project, I was interested in using Airbnb [Seattle Open Data from Kaggle](https://www.kaggle.com/airbnb/seattle) from Jan 2016 to Jan 2017 to answer following business questions:

1. Which kinds of accomodations are listed and how do they make up the price?
2. How big is the connection between number of reviewer comments and the popularity of the objects?
3. Which accommodations of which host were actually booked and which ones generated the most revenue?


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

The main findings of the analysis can be found in the Blog Post available [here](https://).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Appreciative big thanks to Airbnb for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/airbnb/seattle).
