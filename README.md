# Analyzing traffic mortality in the US

## Introduction
In this project, we will be analyzing data on road accidents in the United States to understand patterns in the demographics of traffic accident victims. Our goal is to identify groups of states with similar profiles, in order to create targeted policy action plans to reduce the incidence of road accidents. The data for this project was originally collected by the National Highway Traffic Safety Administration and the National Association of Insurance Commissioners, and was released as a CSV file by FiveThirtyEight under the CC-BY4.0 license.

## Data
The data for this project consists of a CSV file containing accidents' information on the percentage of drivers who were speeding, under the influence of alcohol, and who had not been in an accident before for each state. We will also include data on the number of miles driven in each state to calculate the total number of fatal accidents.

## Methods
We will use a combination of visual interpretation and statistical analysis to identify patterns in the data. Specifically, we will:

- Read in and review the data
- Generate a text and visual summary of the data
- Measure the relationship between features and accidents using the Pearson correlation coefficient and multivariate linear regression
- Conduct PCA on standardized data and plot the first two principal components
- Use KMeans clustering to identify clusters of similar states in the data
- Explore the differences in features between the clusters
- Calculate the number of accidents within each cluster to determine the most appropriate group of states to focus on

## Results
We will present our findings in the form of summary statistics and visualizations. We will also include a discussion of the implications of our results for policy recommendations.
