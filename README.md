# Project.6-Hotel-booking-EDA.

## About

We have a compact dataset to study about the hotel industry, mainly the bookings. This dataset has 32 variables/Columns with around 1,19,390 entries/Rows focussing on two types of hotels category City & Resort. This data set contains booking information for a city hotel and a resort hotel, and includes information such as when the booking was made, length of stay, the number of adults, children, and/or babies, and the number of available parking spaces, among other things. 

## Objective

By the end we will conclude the study with following insights:-
* Best time for booking
* Preferred hotel type
* Optimal duration of stsy
* Distribution Segment and market segments to be focused to increase revenue
* Factors leading to cancellation which affects the revenue.
* Factors like meals, parking spaces, special requests etc. which might affect in the increase of ADR and revenue.
* Marketing stretegy and suggestions

## Workflow

1. Understanding problem statement and Raw data 
2. Exploratory Data Analysis i.e. Data wrangling, cleaning, manupulation.
3. Data Visualization
4. Analysing and sharing the conclusions


# 1. Understanding problem statement and Raw data

Firstly very carefully We understand the problem statement and the questions for which we are doing this study. what we want to find out or can find out from the given data set. then we collect data, import it into the system/software. Here we are using "Colab" for this study. Import libraries such as NumPy, pandas, matplotlib, seaborn.Then load the raw dataset. We read the data and try understand the minute detail like what information each column giving and how usefull it can be for the study. we found out that there are 32 variables/Columns with around 1,19,390 entries/Rows. There were few columns which we felt very important to base our study on i.e. hotel type, ADR, meal type, Cancellation etc. 

# 2. Exploratory Data Analysis

Exploratory Data Analysis refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.

## Data wrangling, cleaning, manupulation

Here start find the abnormality in the data i.e. Null values, missing values, NaNs, redundant values and Outliers, distribution of data.

## Data Cleaning
###   a. Handling Null Values
Company Id and Agent Id: - These columns have null values of 93% and 15% respectively. Hence, these columns are dropped.

Country: - This has null values less than 5% thus the null values are filled with the mode value.

Children and babies: - There are only 4 null values so the null value is filled with mean
 
###   b. Handling Outliers
Outliers are data points that don’t fit the pattern of rest of the numbers. They are the extremely high or extremely low values in the data set or data graph. 
We have used the Interquartile range method to handle outliers. 

## Data Manipulation: - Creating new variable/columns by combining other two columns for an effective study i.e.
Kids= Children +babies

Total stay= stays_in_weekend_nights+ stays_in_week_nights

Guest= Adults+kids

Revenue= stay of non-cancelled guests * ADR

## Data study
### i) UNIVARIATE ANALYSIS: 
Univariate analysis is the simplest form of analyzing data i.e study of one variable. Its major purpose is to describe; distribution of single data, and find patterns in the data.

### ii) BIVARIATE ANALYSIS:
Bivariate analysis between two variables. One of the variables will be dependent and the other is independent. The study is analyzed between the two variables to understand to what extent the change has occurred.

### iii) MULTIVARIATE ANALYSIS
Multivariate data analysis is the study of relationships among the attributes, classify the collected samples into homogeneous groups, and make inferences about the underlying populations from the sample.


# 3. Data Visualization

Data Visualization :-

Data visualization is the practice of translating information into a visual context, such as a map or graph, to make it easier to understand and gain insights from them. 
The graphs used here for study are: -
Box Plot.

Histogram.

Pie Chart.

Bar Plot.

Line Plot.

Scatter Plot.

Geo Mapping.




