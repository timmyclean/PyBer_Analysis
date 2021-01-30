# PyBer_Analysis
# Scope of Project

## Primary
 *  "analyze all the rideshare data from January to early May of 2019 and create a compelling visualization" V.Isualize

### Priamary Tasks 
 * Clean Data
 * Merge Data (csv)
 * Create DataFrames for City types, Fares, Averages
 * Use information to create differnt types of charts to analyze data 

** Charts Analyzing  ( the following charts show preliminary results)
  
  * http://localhost:8888/view/PyBer_Analysis/analysis/Fig1.png
    - We see in this chart that there is a direct relation in terms of population and the amount rides that are taken. In Urban areas the number of rides is high but the average fare is lower. We also see although the Rural rides have higher average fares per ride they are much less frequent. The Suburban fares fall in the middle of the data set. Population is a big factor in the number of rides. 
  
  * http://localhost:8888/view/PyBer_Analysis/analysis/Fig2.png
    - this box and whisper graph for the "Ride Count Data" shows that "there is one outlier in the urban ride count data. Also, the average number of rides in the rural cities is about 4- and 3.5-times lower per city than the urban and suburban cities, respectively".

 * http://localhost:8888/view/PyBer_Analysis/analysis/Fig3.png
    - this box and whisper graph for the "Ride Fare Data" shows "that there are no outliers. However, the average fare for rides in the rural cities is about $11 and $5 more per ride than the urban and suburban cities, respectively". We can assume the difference is due to Rural Rides are longer and therefore more costly, however it seems volume is the key to higher revenue. Individuals would be more inclined to use Pyber in Urban areas due to the percieved value that its "inexpensive, & convenient".
 
 * http://localhost:8888/view/PyBer_Analysis/analysis/Fig4.png
    - the final box and whisper plot for "Driver Count by City Type" shows, "The average number of drivers in rural cities is nine to four times less per city than in urban and suburban cities, respectively" We can conclude again that although competition to get fares is greater in Urban areas its still worth it compared to rural areas.
  
 * http://localhost:8888/view/PyBer_Analysis/analysis/Fig5.png 
    - this pie chart illustrates the percentage of total fares by city type. It validates our thought process that Urban fares are creating a moajority of the revenue.

 * http://localhost:8888/view/PyBer_Analysis/analysis/Fig6.png
    - this pie chart shows the percentage of rides by city type. More people more rides.
  
 * http://localhost:8888/view/PyBer_Analysis/analysis/Fig7.png
    - the final pie chart shows that drivers are more likely to work in more densly populated areas.
  
# New Task
  *  "create a summary DataFrame of the ride-sharing data by city type & create a multiple-line graph that shows the total weekly fares for each city type. Finally, submit a  written report that summarizes how the data differs by city type and how those differences can be used by decision-makers at PyBer" V.Isulaize
  * We merged the data and compiled the following data
      1 - total rides for each city type
      2 - total drivers for each city type
      3 - total amount of fares for each city type
      4 - average fare per ride for each city type. 
      5 - average fare per driver for each city type. 
      6 - Pivoted and reshaped data to show a multi-line graph showing the total weekly fares for each city type.

# Results 
(see corresponding results)

  1- type/total rides
        Rural        125
        Suburban     625
        Urban       1625
          * Individuals would be more inclined to use Pyber in Urban areas due to the percieved value that its "inexpensive, & convenient"
  2- type/Driver Count per City area
        Rural         78
        Suburban     490
        Urban       2405
          * Drivers have a better chance at fares in more populated areas
  3- type/total fares per city type
        Rural        $4,327.93
        Suburban    $19,356.33
        Urban       $39,854.38
           * This Data shows some potential with Suburban city type, the amount of rides is much less and the total amount fares does not show that it is equally great in terms              of revenue generated.
  4-type/ Average Fare per City type
        Rural       $34.60
        Suburban    $30.97
        Urban       $24.52 
            * One can see that the distance has a great effect on the average ride fare. 
   5 - type Average Fare per driver per city type
        Rural       $55.48
        Suburban    $39.50
        Urban       $16.57
            * Therefore higher chances to get fares in Urban areas but need to get three average fares to one fare in the Rural area. Suburban area once again has potential.
   6 - http://localhost:8888/view/PyBer_Analysis/analysis/Pyber_fare_summary.png
          - Pivoted and reshaped data to show a multi-line graph showing the total weekly fares for each city type
            * the graph illustrates many similarities in terms of peaks and valleys correlated to population of city types (assuming Urban are the highest least spread                         population density and that Rural is lowest and most spread out population density, with Suburban in the middle) 

# Summary
   * In conclusion this data can provide Pyber with the knowledge to effectively market and promote its service.
#  Recommendations
  1) Aggressivley market to Suburban market, it would seem they have disposable income, refering to multi-line graph we see spikes in all three categories in the weeks of March,     if Pyber could capture all three markets but specifically the Suburban market to use our service for rides to the airport, restaurants etc. Revenue would be increased.
  2) Offer incentives to Rural Riders, frequency is lower due to cost, time, number of drivers. Therefore if there was a incentive for drivers and riders to use the service          there is no where to go but up in that city type. Incentives could include, Frequency incentives, first time user etc.
  3) Like competitors, Pyber could slightly raise rates for the service in Urban areas at peak times. The Urban user is very convenient focused and may prefer less riders using      the service during peak times.

# Follow up
* ASAP 
