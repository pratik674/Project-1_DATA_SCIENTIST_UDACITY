# Project-1_DATA_SCIENTIST_UDACITY
# 
## Table of Contents
  1. Installation
  2. Project Motivation
  3. File descriptions
  4. Results
  5. Licensing, Authors and Acknowledgements
### Installation
There should be no necessary libraries to run the code here beyond the Anaconda distribution of Python. This code will run with no issues using Python version 3.*
Nevertheless, the libraries that were used for this project includes pandas, numpy, matplotlib and seaborn. 

### Project Motivation

#### Business Understanding

For this project, i was interested in using Airbnb data (2016) from Seattle, U.S.A. 
Airbnb being a primary rental service Industry, includes data obtained from hosts and guests or visitors spread across multiple neighbourhoods. 
The data invokes questions related to multiple factors,not excluding, neighbourhood of choice, cost variation for neighbourhoods across time and number of guests, hosts and listings variation and host revenue. Attempts has been made to answer the following questions :

  a. What is the vibe of a neighbourhood?
  
  b. What is the busiest time of the year to visit Seattle? How does the price vary over time and by how  much?
  
  c. What is the trend of number of hostings and listings over time? 
  
  d. What is the occupancy rate, for thirty days, in the neighborhood? What is the revenue generatedfor the hosts?
  
#### Data Understanding
The data comprises three csv files, calendar, listing and reviews. The calendar contains information about listing ID of the host, the time (yy-mm-dd) and the price at that time. This gives us an id of the pricing trend over a period of time. Listing csv has a plethor of information, related to which host has what type of property in a particular neighbourhood. Guests incoming and extra people add on for a particular type of property booked gives an idea of how much revenue any particular host earns. One can even find which host has generated the most revenue and through what means. Every neighbourhood offers something different and that is reflected in the average property prices. 


### File description
There are four notebooks, pertaining to the above questions. Each of the notebooks is exploratory in searching through the data pertaining to the questions showcased by the notebook title.  

 ##### 1. vibe.ipynb : This shows the pricing of top and bottom most neighbourhoods in Seattle
 
 ##### 2. busy_time.ipynb.ipynb: Explores the pricing and availabilty over the course of an year. 
 
 ##### 3.  trend_guest_hosts_time.ipynb: to find the trend of number of guests and the number of listings provided by the host over a span of 8 years
 
 ##### 4. occupancy_rate.ipynb: analyses the 30 day availability data and presents a picture of which neighbourhood is busy for the next 30 days. Additional total revenue generated neighbourhood wise is also shown via this code. We get an idea , from Airbnb's perspective, the top performing neighbourhoods.

### Results
The main findings of the code can be found at the post available at https://medium.com/@iitkgp.pratik/would-you-rather-be-a-host-or-a-guest-for-airbnb-in-seattle-1336a3f86c92

### Licensing, Authors, Acknowledgements
Must give credit to Airbnb for the data.This data is licensed under a Creative Commons Attribution 4.0 International License.You can find more by following the link here https://www.kaggle.com/datasets/airbnb/seattle. Otherwise, feel free to use the code here as you would like!
