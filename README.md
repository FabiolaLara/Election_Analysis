# Election_Analysis

## Project Overview

1. Overview of election audit

  The porpuse of this election analysis is to retrieve some specific values. To start with, It was asked to determine the Total number of votes, then it is neccesary to calculate the total votes by County, as their percentage in voting respectivately. Finally we have to retrieve the county for the largest voter turnout. 
  
2.Election-Audit Results
  + How many votes were cast in this congressional election?
  
    The number of votes casting for this exercise were: 369,711.
    
  + Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.
    
    Number of votes for each county and percentage of votes for each one.
    * Jefferson: 10.5% (38,855)
    * Denver:    82.8% (306,055)
    * Arapahoe: 6.7%   (24,801)
    
  + Which county had the largest number of votes?
    The county with the largest number of votes is: `"Denver"`
    
  + Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

    * Charles Casper Stockham: 23.0%, (85,213 votes)
    * Diana DeGette:           73.8%, (272,892 votes)
    * Raymond Anthony Doane:    3.1%, (11,606 votes)  
    
  + Which candidate won the election, what was their vote count, and what was their percentage of the total votes?
  
    * The winner for this election was:
    
    **Diana DeGette with `272,892` votes, her porcentage number over the others candidates was `73.8%`.**

3.Election-Audit Summary. In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

  About this analysis we could summarize that it is very useful, we could add some others fields to our data, like the kind of sex for voters so we could make some specific politic proposals, the we could storage the count for each sex in a counter, and have the total for each kind of sex. Another important thing we can do is to evaluate the age for the voters, due it is necesary to know in what kind of fields the candidates have to invest more  for this we need to have one field for the age, then we have to put this values in a list, we order this in ascending form, then we can apply a `for` for all the values in the list, and an `If` condition to make a range of values, with that ranges we could assing to a some `variables` like young, adult, old, etc.

