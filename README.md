# MTA-Turnstile-Analysis

The Challenge
----
WomenTechWomenYes (WTWY), a non-profit organization in New York City, is raising money for their annual gala. To promote the event, street teams are being placed outside subway stations to hand out free gala tickets. WTWY want to use MTA subway data to optimize the placement of their street teams to gather the most signatures, ideally from those who will attend the gala and contribute to their cause.


The Methods
---
Our approach was taking MTA Turnstile Data from April 1, 2018 - June 30, 2018 since we believe that the gala would benefit from campaining two to three months before the gala starts. From there, our group cleaned up the data set by removing duplicate data, removing negative counts, cap 4 hour intervals at 50,000, and remove days with 0 riders. It is worth noting that only 5 percent of the data had one of these characteristics. 

From looking at this clean data, we calculated the average daily total ridership as a baseline evaluation, which resulted in the following stations to promote the event:

          - Grand Central
          - 34 Street Herald Square
          - 34 St-Penn Station
          - 14 St-Union Square
          - 42 St-Port-Auth
          - Time Sq-42 St
          - St Fulton St 
          - 59 Columbus
          - 47-50 STS Rock Flushing-Main


We wanted to add value to the data, so we decided that we would weight our data to census data. The second would be the daily total ridership weighted by the % of NYC's Infromation Tech Workers that are Residents in that Station's Zip Code, which resulted in the following stations to promote the event:

          - 14 St-Union Sq 
          - 34 St-Herald Sq
          - 34 St-Penn Sta
          - Jay St-Metrotec 
          - Bedford Av
          - Borought Hall
          - 59 St Columbusm 96 St
          - 14-ST-Union Sq
          - W 4 St-Wash Sq
          
          


