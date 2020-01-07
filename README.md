# Flight-Delay-Analysis

1. DATA PREPARATION
The dataset is about The U.S. Department of Transportation’s (DOT) Bureau of Transportation Statistics, which contains more than 5 million records of the flights’ information during 2015, including the carrier of the airline, the original airport, destination airport, the distance of the flight, the time spent, the departure delay time, and arrival delay time, etc. I used this dataset to build the regression models to predict the delays of flights.

2. EXPLANATORY DATA ANALYSIS
First, I cleaned the data, performed the explorary data analysis, and visualized the data to get some insights from them. After that, I built the regression models and predict the delays of the airlines.
- visualization: matplolib, seaborn, basemap
- data manipulation: pandas, numpy

3. Building the models
- modeling: sklearn, scipy
- class definition: regression, figures

4. Conclusion
It is concluded that maximum arrival Delays are dependent on the Departure Delays of the Airport. 
We can see that departure delay is the main problem which is creating Delay in the airport. Departure Delays can be caused due Security Delay, Airline System Delays, Airlines Delay etc. Delays can influence the incomes of the airlines so it had to deal with it properly and reduced to maximize the profits of airlines.
