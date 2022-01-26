Assignment of IBM's data science capstone course

# Classifying universities neighborhoods
#### Lucas Falcão Silva
#### 03/2020
## 1. Introduction: why analyze it?
In this report, I analyze universities' neighborhoods (from USA) using foursquare data. Therefore, we can classify universities based on its surrounds. This could help young people select a university with a neighborhood with the qualities that they prefer, and the universities by letting they know possible attractiveness points. With this information both future college students and university administrators could improve their decision making. And their a third public to this analysis: entrepreneurs seeking to invest in a business related with college audience. They could see the classes od university and explore possible demands.
## 2. Data
This could be done by one data frame with a list of universities and its latitude and longitude. This website contains exactly what we need, however it doen’t cover all US universities (only 49). We can import this table as a data frame trough web scraping in python. Here is the five first rows of the universities with location data: Then, with the latitude foursquare API we can make a request to access data of local venues close to each university and its category of business.
## 3. Methodology and analyzes
With all data merged, we used K-Nearest Neighbors analyzes to identify the similar classes of universities based on their venues commercial/entertaining places. We also plot a map to visualize their distribution in space.
Based on the results of the KNN algorithm, we can see that most universities fall on the same class: with a lot of quick meals shops (pizza, coffee, bagel) and collegerelated entertainment. I.e., 77,5% of the colleges are similar. 
This number (77%) is considerable high, means that universities could favorable certain business. Therefore, the other categories might need business or could be a unique factor to differentiate the university from others.
