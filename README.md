
# Citi-Bike-Analytics

![alt text](https://d21xlh2maitm24.cloudfront.net/nyc/Annual-Membership-Image.png?mtime=20170331121650)

<p align="center">
  <a href="#background">Data Source</a> •
  <a href="#analysis">Findings</a> •
  <a href="#technology-stack-used">Technology Used</a>
</p>

A analysis for the New York Citi Bike Program, in which responsible for overseeing the largest bike sharing program for 200,000+ data points in the United States
 in order to generate business insights in terms of visulize the peak time in both summer and winter period and the top start location in New York City and Jersey City, New Jersey
 
* View complete dashboard [here](https://public.tableau.com/profile/davidgu#!/vizhome/citibikeanalysis/Forcityofficials?publish=yes)

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/top_location.png)

## Data Source
![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/citibikedata.png)

This [Citi Bike Data](https://www.citibikenyc.com/system-data) has been processed to remove trips that are taken by staff as they service and inspect the system, 
trips that are taken to/from any of our “test” stations (which were using more in June and July 2013), and any trips that were below 60 seconds in length 
(potentially false starts or users trying to re-dock a bike to ensure it's secure).

* Limitation
There were 7% user did not provide gender information and most of them (14%) are weekend users so we will not be able to tell if female are more willing to ride
on the weekend then they do on weekdays, but we may still determine that male user are the dominant customer at all time

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/limitation.png)


## Findings 


### The current main citi bike riders fall into young male group between 18 -20 but number of femal reiders increases over time as they are showing interest to start riding during the weekend

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/customer_base.png) ![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/femal_ridership.png)

### The 1st and 2nd peak hours during a day would usually be 7-8 AM and 5-6 PM season-regardless 

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/peakhours.png)


### As the temperature gets cold as winter begins, people tend not to ride as well because of the lack of comfort individuals face when riding in
low temperatures. Therefore, at some point the ridership does not grow. However, the total amount of annual member have been kept increased over time in 2017

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/2017_growth.png)


### Map visualization helps to understand that more and more people choose to live in Jersey City and work in Manhathan

![alt text](https://raw.githubusercontent.com/david880110/Citi-Bike-Analytics/master/image/popular_location.png)

## Technology Used

-   Python
-   Tableau
