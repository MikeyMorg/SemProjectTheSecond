## Abstract
    This notebook will be used to analyze data, so we can make predictions on if someone has a sleep disorder or not.
    The data that we will be analyzing contains different lifestyle, physiolgical and demographic factors
    that we will use as our training metrics to be able to predict if there is a sleeping disorder present.
    This data comes from a Kaggle Competition, https://www.kaggle.com/competitions/sleep-disorder-prediction-challenge.

## Data
    The training data given to us is within a sub-folder labeled 'data', under train_data.csv.
    Our testing data is within the same subfolder, labeled under test_data_competition.csv. We also utilize data from 
    https://www.cdc.gov/brfss/annual_data/annual_2014.html. We use our model that we performed on our training data set onto this model,
    as it seems that the training set is mainly, if not entirely, synthetic data and we want to see if our model will yield results on
    real data.

## Requirements
    Attached in this folder is a requirements.txt file that can be used to check the requirements needed
    for your environment when wanting to run this code.

## SemProject
    This subfolder was created when we made our virtual environment. This can be ignored/deleted, and you can make your own virtual environment and
    download all the requirements. This can be done by running the command 'pip install -r requirements.txt' in your terminal after creating your virtual environment.

## src Folder
    The sub-folder, src, will have our jupyter notebook, titled 'SemProj.ipynb' where we unpacked the data,
    analyzed it and started our prediction process. Furthermore, is another jupyter notebook, titled 'brffsEDA.ipynb'.
    This notebook is further EDA, and utilization of a Decision Forest model on another dataset on sleep disorder and lifestyle
    factors.

    We also have a jupyter notebook called 'SQL_Sleep.ipynb' which is used to show an SQL implementation of our Kaggle Competition data, in
    regards to using SQL to make a database and queries instead of the pandas dataframes that we made in the original file of 'SemProj.ipynb'.
