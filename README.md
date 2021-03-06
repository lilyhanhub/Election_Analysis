# Election_Analysis

## Overview of Election Audit
The purpose of this election analysis is to audit for the Colorado Board of Elections to determine the winning candidate and the largest voter turnout based on county. The analysis required the follwing data to be presented:
* Total number of votes cast
* A complete list of counties with the voter turnout and percentage
* The county with the largest turnout
* A complete list of candidates who recieved votes
* Total number of votes each candidate received
* Percentage of votes each candidate won
* The winner of the election based on popular vote

## Resources
* Data Source: election_results.csv
* Software: Python 3.9.12, Visual Studio Code, 1.68.0

## Election Audit Results
The congressional election analysis audit shows that:
* There were a total of 369,711 votes cast: 10.5% of the votes coming from Jefferson county (38,855), 82.8% of the votes from Denver county (306,055), and 6.7% from Arapahoe county (24,801). 
* The county with the highest voter turnout was Denver county at 82.8% of all votes cast.
* There were three candidates: 
  * Charles Casper Stockham received 23% of the votes (85,213).
  * Diana Degette received 73.8% of the votes (272,892).
  * Raymon Anthony Doane received 3.1% of the votes (11,606). 
* The winner of the election was: Diana Degette who received 73.8% of the votes and 272,892 number of the votes. 

![Screenshot of the election results](/Resources/election_results.png)

## Election Audit Summary
[This python code](/PyPoll_Challenge.py) written for the Colorado Board of Elections has successfully accomplished all the requirements, which proved that it could serve as a framework to analyze dataset of big scales for the future election use.
* The script can be applied to any electoral tabular dataset simply by changing the source of the data, as there would be different candidates or different counties. 
* Also, It's easy to modify the script for any sort of elections, either a congressioanl or a state/local election, by modifying the county to the targeted region, which could be a state or a city. 

