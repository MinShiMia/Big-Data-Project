# This repository contains the files for our big data group project. 

# Statement: 
Accidents caused by large trucks remain one of the leading causes of injuries and deaths in the United States.

Hence, in order to capture the driving behavior of its truck drivers, ANT corporation has equipped its trucks with a device to log location and event data to increase safety. 

# Objectives: 

1) Identify dangerous commercial truck drivers; 

2) Create an analytical dashboard for illustrations.

# Flowchart:

![Flowchart](https://MinShiMia.github.io/Big-Data-Project/BigDataProjectFlowchart.png)

1) We first utilize big data Hadoop ecosystem to process geospatial data, including database and tables creation, data ingestion, transform.

2) Then, we perform data exploration and visualization in Tableau by connecting to Hadoop ecosystem server.

3) Besides, we modeled the regression relationship between factors and truck driver accident risks by connecting to R and external analysis in STATA.

4) Finally, we draw our conclusion and propose suggestions on how to lower the probability of large trucks accidents.


# Table Relationship:
![Table Relationship](https://MinShiMia.github.io/Big-Data-Project/BigDataProjectTableRelationship.png)

# Business Question 1: Who are the most and least risky drivers?
![Business Question 1](https://MinShiMia.github.io/Big-Data-Project/BigDataProjectQuestion1.png)
Answer: Most risky driver: A73 (10 risk factor); Least risky driver: A2 (0.966 risk factor)


# Business Question 2: Which city has the highest risk factor?
![Business Question 2](https://MinShiMia.github.io/Big-Data-Project/BigDataProjectQuestion2.png)
Answer: City with highest average risk factor: Hollister (with risk factor 5.498)


# Business Question 3: What's the relationship between events and risk factor?
![Business Question 3](https://MinShiMia.github.io/Big-Data-Project/BigDataProjectQuestion3.png)
Answer: Unsafe following distance causes highest number of unnormal event.


# Business Question 4: What's the relationship between MPG/Velocity and risk factor?

![Business Question 4](https://MinShiMia.github.io/Big-Data-Project/BigDataProjectQuestion4.png)
Answer: MPG or Speed does not have obvious relationship with risk factor.


# Business Question 5: What's the relationship between truck model and risk factor?
![Business Question 5](https://MinShiMia.github.io/Big-Data-Project/BigDataProjectQuestion5.png)
Answer: Different tuck model has different frequency of unnormal events, thus different level of risk factor.


# Business Question 6: Using linear regression and correlation to explore the factors affecting risk factor ~
![Business Question 6](https://MinShiMia.github.io/Big-Data-Project/BigDataProjectQuestion6.png)
Inference: risk factor is almost perfectly correlated with only the number of events


# Conclusions & Suggestions:
1) Risk factors are not dependent on MPG/Velocity, it is perfectly correlated with count of unnormal events.

2) Most unnormal event occurring city is Willits, it may be worth to analyze further on that, if local factors, such as traffic, road conditions, road maps are related to the risk factors. 

3) Top 5 Risky drivers can be counseled about unsafe driving and consequences and given more training if needed. 

4) Since Unsafe following distance is the most occurring event and it affects the risk factor most, an alert system can be installed on all the trucks which will notify the drivers if they have crossed the threshold of safe distance. 





