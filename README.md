# CIA Country Analysis and Clustering

### Goal

+ Using K-Means gain insights into similarities between countries and regions of the World
+ Source: All these data sets are made up of data from the US government. 
https://www.cia.gov/library/publications/the-world-factbook/docs/faqs.html

### Exploratory Data Analysis

#### Task 1: Creating a scatterplot showing the relationship between Phones per 1000 people and the GDP per Capita

+ Coloured by region

#### Task 2: Creating a scatterplot showing the relationship between GDP per Capita and Literacy

+ Coloured by region

#### Conclusions

+ 
+ 
+ 

#### Task 3: Creating a heatmap of the correlation between columns in the DataFrame


### Data Feature Preparation

+ Prepare the data for clustering
+ Use the get_dummies functions to turn non mathetical columns into dummy variables
+ Use the Standard Scaler due to the different types of measurements
+ Create and Fit KMeans Model
+ Model Interpretation


### Creating and Fitting Kmeans Model

+ Use a for loop to create and fit several Kmeans models testing anywhere from 2 to 30 models
+ Keep track of the sum of squared distances for each K value
+ Plot it out to creare an "elbow" plot of K versus SSD
