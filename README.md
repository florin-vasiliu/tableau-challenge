# <a href="https://public.tableau.com/profile/florin.vasiliu4232#!/vizhome/Analysisv2_15935802632930/Story?publish=yes"> City Bike Analytics </a>


  The dataset used for the analysis consisted of May.2020 <a href="https://s3.amazonaws.com/tripdata/index.html">CityBike data</a>. In order to calculate the efficiency of the bikes, one extra column was added to the base dataset using python, which consists of the bike's next trip time, therefore defining also the idle time besides the trip 
duration for each bike.
 
  Firstly, the analysis has been developed in order to answer the following questions:

1. Who are the clients? <br>
The clients are users between age 15 and 75 (mostly between 25-35), the majority being males (males > 80K trips vs. females < 60k trips). <br>
(see sheet <a href="https://public.tableau.com/profile/florin.vasiliu4232#!/vizhome/Analysisv2_15935802632930/DurationByAge">DurationByAge</a>).

2. Do users prefer to subscribe? <br>
The majority of the trips are with subscription (approx. 100k w/ subscription vs. approx 40k w/o subscription), but the trip duration is 
shorter (avg trip duration w/ subscription - around 25 [min] vs. w/o subscription - around 40[min]).<br>
(see sheet <a href="https://public.tableau.com/profile/florin.vasiliu4232#!/vizhome/Analysisv2_15935802632930/UtilizationByHourOfTheDay">UtilizationByHourOfTheDay</a>).

3. Which are the hours of the day where bikes are used more? <br>
The bike utilization starts increasing from 20% at 6:00 AM up to 60% at 2:00 PM, drops back to 20% at 8:00PM and stays constant during the night.<br>
(see sheet <a href="https://public.tableau.com/profile/florin.vasiliu4232#!/vizhome/Analysisv2_15935802632930/UtilizationByHourOfTheDay">UtilizationByHourOfTheDay</a>).

4. Where is the highest trafic? <br>
The highest trafic is in the Western part of the city, where most of the stations record between 1 and 5 thousand bikes during the May.20 timeframe.<br>
(see sheet <a href="https://public.tableau.com/profile/florin.vasiliu4232#!/vizhome/Analysisv2_15935802632930/BikeTrafic">BikeTrafic</a>).

5. Where are the bikes less used? <br>
The bikes are used less in the South part of the city, where most of the stations record more than 10 hours of bike idling time in average.<br>
(see sheet <a href="https://public.tableau.com/profile/florin.vasiliu4232#!/vizhome/Analysisv2_15935802632930/IdleTimePerEndStation">IdleTimePerEndStation</a>).

6. Are bikes available during the day at all stations? <br>
Bikes are mostly available in the high trafic zone, during the high utilization timeframe, where more than 5 bikes in average pass through a station
within one hour.<br>
(see sheet <a href="https://public.tableau.com/profile/florin.vasiliu4232#!/vizhome/Analysisv2_15935802632930/BikeAvailability">BikeAvailability</a>).

  Secondly, two interactive dashboards have been developed to explore: end stations with most/least utilization (dashboard <a href="https://public.tableau.com/profile/florin.vasiliu4232#!/vizhome/Analysisv2_15935802632930/TopBottomStationsIdleTime">Top/BottomStations&IdleTime</a>) and hourly indicators for avg. trip utilization, number of trips, avg. trip duration and bike availability (dashboard <a href="https://public.tableau.com/profile/florin.vasiliu4232#!/vizhome/Analysisv2_15935802632930/StatsBikeAvailability">StatsBikeAvailability</a>).
  
  Finally, the story has been developed to encapsulate all the topics mentioned above (<a href="https://public.tableau.com/profile/florin.vasiliu4232#!/vizhome/Analysisv2_15935802632930/Story">story</a>).
  
