
# Project: ﻿Carpool Application: Plots for the Data Analytics tab with pre-generated data
## Premise of the project: This project is part of a Hackaton competition. The topic of the competition is Green Offices. My team from CAB decided to create a carpoolapp which aimed to allow emplyees to post and book shared rides within the company. The app will be used by employees who work in industrial areas where public transportation is weak and people need to drive by car in order to get to their office. Example (Main office of DocMorris: 43 minutes by public transport and 8 minutes by car. The app will promote sustainability by reducing CO2 emissions. The companies whould be able to share their results in section3 of their ESG reports.

## Data:
+ GPT generated
+ Rides Dataset: 250 rides 
+ Users dataset
+ Locations dataset: pre-decided locations with their coordinates
## Libraries used: 
+ Data Management:
Data Handling: Manipulating and analyzing data with pandas.
Database Interaction: Storing and retrieving data from MongoDB(This is the main database used for the app but I have used CSV files to create the charts for the presentation and with the generated data.
+ Data Visualization:
Interactive Visuals: Creating interactive charts and dashboards with plotly and matloptlib.
+ Configuration Management:
Environment Variables: Managing configuration and sensitive information using dotenv.
+ Date and Time Handling:
Time-Series Analysis: Utilizing datetime for time-based data analysis. I have also tried to create a ML model which will forecast the saved CO2 emissions but based on the limited 'fake' data we have decided to postpone this step for now.


## Step 1 (testing the MongoDB database)
+ Testing the extraction of data from MongoDB and plotting something random (file: First_test.ipynb)
## Step 2 (file: Plot_1.ipynb)
+ Plot pie chart showing number of rides per Departments
+ Plot pie chart showing number of rides per Teams
+ Test different plots in order to show which routes were most popular
+ Butterfly Chart which is sorted by station names from the city to the office and from the office to the city
## Step 3 (file: map_hackaton.ipynb)
+ Tested if we could integrate a folium map in folium
+ The real map is created by another team memeber and represents all possible pick up locations (we do not have the file in this repository)
## Step 4 (file: Line_charts.ipynb)
+ Plot line chart showing number of rides per Month / Week / Day
+ Test matplotlib and plotly to see which chart will look better on the website
+ Plot a pie chart which shows totla number of emissions saved

## Future steaps 

+ Use a predicting model which will tell us how many emissions will be savsed if the employees keep on using the app
+ each user will have their own analytics with the emissions they saved
+ Plot more charts: example ( YOY Growth of rides and saved emissions) dicovering more patters and seasonality (when we have more real data)
## Link to the presenation: https://www.canva.com/design/DAGXtqkgXwk/xAmkA8967p5cCYUrJT5WUg/view?utm_content=DAGXtqkgXwk&utm_campaign=designshare&utm_medium=link&utm_source=editor
  

