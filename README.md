# Investigating the Airbnb Seattle Dataset between 2016 and 2017 

## Understanding the Business and the Datasets

Airbnb have offerred a more unique and personalized way to its guests and hosts since 2008. The Airbnb Seattle dataset is part the Airnb Inside initiative and describes the listing activity of homestays in Seattle, WA. The dataset contains the activities in Seattle between 2016 and 2017. 
The dataset includes 3 seperate datasets. These are listings, reviews and calendar. 
- The Listings contain full descriptions and average review score.
- The Reviews contain unique id for each reviewer and detailed comments.
- The Calendar contain listing id and the price and availability for that day. 

### Questions:

1. When do people visit Seattle mostly? Is there a particular month or a season that the Airbnb prices are high in Seattle?

2. Does a neigbourhood affect the listing price? What are the most expensive listing price and the least expensive listing price in Seattle neighbourhoods?

3. Can we predict a listing price in Seattle Airbnb? What are the key variables for predicting a listing price?

## Understanding and Assessing the datasets

In this project, multiple Python data analysis libraries were used. These are Numpy, Pandas, Matplotlib, Sklearn, Collections and Seaborn. After importing the related libraries, 3 separate datasets (reviews, calendar and listings) were loaded and read for further evaluations. 

Data wrangling and cleaning process were applied to prepare the datasets for exploratory visualizations and modelling. Data cleaning steps includes; dropping some columns, changing data types, removing signs and texts from the rows and columns, filling missing values by mean, mode or median of the columns and removing the missing values if needed. 

## Findings

1. People mostly visit Airbnb Seattle in summer. The highest prices in Seattle Airbnb listings are between June and August. July is the most expensive month and the avarage listing price in July is around $150.

2. After August the listing prices start decreasing and increases again in December. 

3. The most common property types in Airbnb Seattle are houses and apartments. 

4. The boats are the most expensive listings in Airbnb Seattle. The avarage listing price for a boat is $283.

5. The most expensive listing is in Southeast Magnolia neighbourhood and its avarage is $231. 

6. The least expesive listing is in Rainier Beach neighbourhood and its avarage is $68.5. 

7. LinearRegression was used for predicting listing prices in Airbnb Seattle.  

8. Based on the data, the rsquared score on the training data was 0.584 and the rsquared score on the test data was 0.589.
6. The most impactful features that affect the prices in Airbnb Seattle are the information about the host (host's name,  membership length of the host, host's picture) and the details of the listing (description, neighnourhood review).



#### Acknowledgement and References
This dataset is part of the Airbnb Inside and it is obtained from Kaggle. Udacity Data Science Nanodegree-Introduction to data science course, Github, Stackoverflow.



