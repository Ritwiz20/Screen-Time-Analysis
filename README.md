# Screen Time Analysis
Screen Time Analysis is a project that aims to analyze and create a report on the amount of time spent on different applications and websites by the user. This project provides a visual report that helps you know how much time you spend on different kinds of applications and websites using your device.

## Dataset
The dataset used in this project contains information about the usage of applications, the number of notifications from applications, the number of times apps opened, and the date. It can be found in the file :  Screentime-App-Details.csv

## Dependencies
To run this project, you need to have the following dependencies installed:

pandas ,
numpy ,
plotly.express ,
seaborn.

## Exploring Dataset
Before analyzing the dataset, you need to import the required dependencies and load the dataset using pd.read_csv(). Once the dataset is loaded, you can explore it using df.info() to get information about the dataset and df.describe() to get descriptive statistics. You can also check for any null values using df.isnull().sum().

## Visualization
To visualize the data, this project uses Plotly and Seaborn libraries. You can plot a bar graph to find out the total usage of different applications and the number of notifications received from them. You can also plot a bar graph to visualize the number of times each application is opened. Additionally, you can use a scatter plot to find the relationship between the number of notifications and the amount of usage and the relationship between the number of notifications and the number of times the application is opened.

## Inference
Based on the visualizations, we can infer that there is a linear relationship between the number of notifications and the amount of usage and the number of times the application is opened. It means that more notifications result in more use of smartphones. This project helps to understand the usage of different applications and websites and their impact on the user's time.
