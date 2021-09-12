# covidtracker
COVID Tracker Project
As COVID-19 Coronavirus cases began to escalate in late December of 2019, It became very important to analyze and monitor covid related data and made public information from various government bodies and agencies such as the Center for Disease Control and Prevention (CDC) and the World Health Organization (WHO).



This COVID Tracking Project collects information from 50 U.S. states and 5 other U.S. territories to provide the most comprehensive testing data we can collect for the novel coronavirus, SARS-CoV-2.

This repository is for the project's website:https://fervent-ardinghelli-073a7d.netlify.app/

The purpose of the project is to infer the rate at which confirmed cases of COVID-19 are growing (or were growing) in various countries.

The website pulls data from ourworldindata.org and then shows the Total Number of cases worldwide using Visualization of Map
![alt text](https://i.ibb.co/wR8BqLd/Screenshot-2021-09-12-at-9-10-02-PM.png)
 
Along with it, we used Graphs to show cases per million countries wise 

 ![alt text](https://i.ibb.co/CPkJzqN/Screenshot-2021-09-12-at-9-11-17-PM.png)
 
 
 
 
Along with it We have done following steps for the US:
List the total number of confirmed cases by US state & list US locations with the most cases
Attempt to fit the time series of confirmed US cases to both an exponential and a logistic function
Use these curve fits to infer doubling times (i.e., time for the number of confirmed cases to double)
If the curve fit was successful, summarize doubling times for each US state with at least 50 cases
The main conclusion is that the doubling time of confirmed cases for countries with many cases is generally on the order of 2 days.

Important Caveats:


This analysis uses data on the confirmed cases as reported by countries, which is lower than the actual number of cases in each country.
Confirmed cases and actual cases in the population grow at different rates. For example, if a country suddenly ramps up testing, then the number of confirmed cases will rapidly rise, but the actual cases may not be rising as fast. So the doubling time for confirmed cases is not the same as the doubling time for actual cases.
Since we're using the entire timeline to infer the doubling times, these are not the current or most recent doubling times. Instead, for countries where the growth is exponential, the inferred doubling time is indicative of the overall rate of growth.
For countries where the growth is no longer exponential and the number of cases is stabilizing (such as Mainland China), we fit the growth curve to a logistic function. Here, the inferred doubling time represents the growth encountered during the initial exponential stage of the epidemic (i.e., in the past).
