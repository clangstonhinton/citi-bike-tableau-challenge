# citi-bike-tableau-challenge
Create data visualizations of the Citi Bike ride sharing program in Tableau.

<img width="1152" alt="Citi Bike Copy for Readme Size" src="https://user-images.githubusercontent.com/44728723/232316050-b5518834-3aa5-41d2-bbcc-b341cb012246.png">


## Background
Since 2013, the Citi Bike ride-sharing program has grown to become largest in the world with an average of 2.7 million rides per month. The program has implemented a robust infrastructure for collecting data on the program's utilization. Each month, bike data is collected, organized, and made public on the Citi Bike website [here](https://s3.amazonaws.com/tripdata/index.html). 

## Data Description
For this analysis, 60 million records were systematically sampled across the two year period ending March 31, 2023. The sampled dataset can be found [here](https://drive.google.com/file/d/1bSDqEYENJ3XRnTIuZgrPpYQSA4gDqB41/view?usp=sharing). (Please note that the sampled dataset and the original data files are not uploaded on GitHub due to the size of the files.) The sampled dataset contains the following columns:
- Ride Id
- Rideable Type (type of bike rented: docked, classic or electric)
- Started At (date and time the ride started)
- Start Station Name
- Start Station ID
- Ended At (data and time the ride ended)
- End Station Name
- End Station ID
- Start Station Lat/Lng
- End Station Lat/Lng
- Member Casual (designnation between member/subscriber or causal/non-member rider)


## Questions to Answer:
- How has ridership grown during the two year period?
- Is there seasonality to the volume of rides within a year?
- Do the peak riding hours differ between warmer months and cooler months of the year?
- What are the Top 10 stations for starting a ride in the most recent month?  Ending a ride?
- How has the proportion of short-term "causal" customers and annual subscribers or "members" changed during the two year period?

## Tableau Visualizations

### Ridership Growth
Total Rides increased by 13% (+3.7M) in the 2nd Year for a total of 32MM rides.  For the 2-year period, a total of 61M rides were measured.
<img width="584" alt="Screen Shot 2023-04-16 at 10 58 27 AM" src="https://user-images.githubusercontent.com/44728723/232321699-facd707e-f8c8-42d5-bd93-a35843dda07f.png">


### Top 10 Stations
The majority of the Top 10 stations for starting a ride are the same as the Top 10 for ending a ride. The stations do not appear to be near points of interest or major metro stations, suggesting that riders may primarily use Citi Bikes for commuting to/from work.
<img width="586" alt="Screen Shot 2023-04-16 at 10 58 34 AM" src="https://user-images.githubusercontent.com/44728723/232321713-1bdc4cd7-5ff0-4171-9353-405ae4be6f5a.png">


### Seasonality
Not surprisingly, the most rides occurred in the Spring - Summer months between May and September of both years.
<img width="609" alt="Screen Shot 2023-04-16 at 10 58 42 AM" src="https://user-images.githubusercontent.com/44728723/232321717-d7b11cb0-e2d6-4c88-abb2-3b9d499e7cf1.png">


### Peak Riding Hours
Peak riding hours are similar in the warmer months and the cooler months.  However, the number of riders is higher in the former.
<img width="597" alt="Screen Shot 2023-04-16 at 10 58 52 AM" src="https://user-images.githubusercontent.com/44728723/232321724-5d58d5e7-2baa-42e4-862c-2a8f06cf2434.png">







