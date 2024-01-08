# tableau-challenge
Data Source
Monthly CSV files (September 2023- November 2023) were collected from Citi Bike Data webpage.

Since the data from the CitiBike website was stored in .csv files and consisted of 1000s of rows, I wanted to consolidate all of this data into one csv file that I would upload to Tableau. 
To accomplish this task I used the Pandas library in Jupyter Notebook to consolidate all of the files. 
<img width="573" alt="Pandas - Tableau Challenge" src="https://github.com/jwoot90/tableau-challenge/assets/35399563/f53d5b81-c2ae-4cd5-9108-858b7b1a2386">







I converted the concatenated files to a dataframe, which I then exported as a csvfile. My analysis consisted of 6 dashboards. 
1.	Top 10 Departure Stations
2.	Bottom 10 Departure Stations
3.	Top 10 Arrival Stations
4.	Bottom 10 Arrival Stations
5.	Bike Usage Data
6.	Additional Usage Data

1.	Top 10 Departure Stations
a.	For this dashboard I examined the top 10 stations for riders to begin their trips between September and November of 2023.
b.	In addition to using a bar chart which examined the number of riders which began their trips, I wanted to pair this data with a detailed map that plotted the location of these stations to examine possible influences for the popularity of these stations. 
<img width="494" alt="Top 10 Departure Stations" src="https://github.com/jwoot90/tableau-challenge/assets/35399563/096ae4c8-2cf7-4d2d-b9a7-05625e06e67d">



2.	Bottom 10 Departure Stations
a.	For this dashboard I examined the bottom 10 stations for riders to begin their trips between September and November of 2023.
b.	In addition to using a bar chart which examined the number of riders which began their trips, I wanted to pair this data with a detailed map that plotted the location of these stations to examine possible influences for the lack of popularity of these stations. 
<img width="502" alt="Bottom Departure Stations" src="https://github.com/jwoot90/tableau-challenge/assets/35399563/95a89bb5-318d-490c-b753-1911bb36c4dd">


3.	Top 10 Arrival Stations
a.	For this dashboard I examined the top 10 stations for riders to end their trips between September and November of 2023.
b.	In addition to using a bar chart which examined the number of riders which began their trips, I wanted to pair this data with a detailed map that plotted the location of these stations to examine possible influences for the popularity of these stations. 
<img width="502" alt="Top 10 Arrival Stations" src="https://github.com/jwoot90/tableau-challenge/assets/35399563/aa82079b-aba2-442f-81c1-e1b373c0ff29">


4.	Bottom 10 Arrival Stations
a.	For this dashboard I examined the bottom 10 stations for riders to end their trips between September and November of 2023.
b.	In addition to using a bar chart which examined the number of riders which began their trips, I wanted to pair this data with a detailed map that plotted the location of these stations to examine possible influences for the lack of popularity of these stations.
<img width="506" alt="Bottom Arrivals" src="https://github.com/jwoot90/tableau-challenge/assets/35399563/8003db02-f7a9-44de-889a-4bfe6a51efa8">


5. a. This dashboard examines rider usage by hour between September and November of 2023 using a heatmap
<img width="500" alt="Usage Heat Map" src="https://github.com/jwoot90/tableau-challenge/assets/35399563/e835676b-1f64-4478-b5d3-916af095e183">

6. a. The last dashboard examines casual and member ridership
Takeaway: Riders which were party of the member category had an average 77% more ridership than the casual riders over the 3 month period. 
b.	Riders who used classic bikes were compared with riders who used electric bikes for the second chart on this dashboard. 94% of riders used classic bikes as opposed to 6% of users who used electric bikes. 
<img width="506" alt="additional usage data" src="https://github.com/jwoot90/tableau-challenge/assets/35399563/70514ed8-d067-4d06-b428-d3a9f997a068">

