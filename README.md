# Write-A-Data-Science-Blog-Post

Udacity Data Science Nanodegree Project

## Description

This is the first project requirement of Udacity’s Data Science Nanodegree program. For this project, students are asked to create a blog post and Github repository to begin building a data science portfolio. 

## Table of contents

- [Installation](#installation)
- [Project motivation](#project-motivation)
- [File descriptions](#file-descriptions)
- [Credits](#credits)
- [Results](#results)

## Installation

The code can be executed using Jupyter Notebook. 
If you don't have Anaconda installed yet, see documentation here: https://numpy.org/install/

## Project Motivation

This project has two main components. 
1.	Create a Github Repository, where I need to upload the Jupyter Notebook code of the model.
2.	Write a blog post to communicate my findings or insights. 

Key Steps to complete this project:

1) Pick a dataset from recommended datasets or choose own dataset. 
   - For this project i chose to work on the recommended dataset for AirBNB Boston Data
    
2) Pose at least three questions related to business or real-world applications of how the data could be used.
    - Q1. What features or variables that will show popular listing?
    - Q2. What available data that would indicate high review score?
    - Q3. Which property features could have impact better or higher rental rates?
3) Create a Jupyter Notebook: 
    - Prepare data:
      - Gather necessary data to answer the questions
      - Handle categorical and missing data
      - Provide insight into the methods you chose and why you chose them
    - Analyze, Model, and Visualize
      - Provide a clear connection between your business questions and how the data answers them.

    - Checkout file: BlogPost Boston AirBNB.ipynb

4) Communicate your business insights:
      - Create a Github repository to share your code and data wrangling/modeling techniques, with a technical audience in mind
      
        - https://github.com/lovelinarichter/Write-A-Data-Science-Blog-Post
      
      - Create a blog post to share your questions and insights with a non-technical audience
      
        - https://medium.com/@lovelina.richter/what-property-features-influence-the-rental-rate-of-homestays-in-boston-ma-212815edc52d?source=friends_link&sk=563edfbb549859f402ec2ff7aae89768

## File descriptions

1. BlogPost Boston AirBNB.ipynb - Code to build the model using Jupyter Notebook
2. BlogPost Boston AirBNB.html - downloaded HTML copy of the code
3. README.MD - Information about this project

## Credits: 

Code dependencies and Libraries

Boston AirnBNB Data is publicly available trhough Kaggle: https://www.kaggle.com/airbnb/boston

The dataset include the following:
1.	Listings - listing information, hosts information, review score. The file contain 3,585 records, 95 columns
2.	Reviews - Review comments. The file contain 68,275, 6 columns
3.	Calendars - availability and price for the day. The file contain 1,308,890 records, 4 columns

The project used the following libraries:
numpy
pandas
matplotlib.pyplot
seaborn
sklearn

References:
https://www.kaggle.com/airbnb/boston https://www.programiz.com/python-programming/docstrings 

https://stackoverflow.com/questions/55937430/python-how-to-remove-sign-andspace#:~:text=You%20can%20use%20str.,the%20%24%20with%20a%20empty%20character. 

https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.to_numeric.html

https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestRegressor.html

## Results

The results are documented throughout the code and on blog post. 

Summary of Result:  The analysis covered one year of AirBNB Boston data from Sept 2016 to Sept 2017. The result of the analysis showed that room type could influence higher rental rate. In addition to room type, other features such as neighborhood, property type, and bed type could influence the rental rate. Other variables that were included in the analysis, but doesn’t appear to have impact on prices are instantly bookable and verified host identity. Finally, I looked at features that could have correlation to higher reviews, but the data doesn’t show any correlation.
