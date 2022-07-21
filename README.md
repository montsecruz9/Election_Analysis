# Election_Analysis

## Project Overview
We are helping the Colorado Board of Elections to analyze vote results from a recent local congressional election. We've been given the following tasks in order to complete the election audit and certify this US congressional race.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received. 
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote. 

## Resources
- Data Source: election_results.csv
- Software: Python 3.7 (64 bit), Visual Studio Code 1.38.1

## Summary
The analysis of the election shows that: 
- There was a total of 369,711 votes cast in the election.
- The candidates were:
  1)Charles Casper Stockham
  2)Diana DeGette
  3)Raymon Anthony Doane
 - The candidate results were:
  - Charles Casper Stockham had a total of 85,123 votes, meaning he reached 23% of the total votes. 
  - Diana DeGette had a total of 272,892 votes, meaning she reached 73.8% of the total votes
  - Raymon Anthony Doane had a total of 11,606 votes, reaching only the 3.1% of the total votes.
 - The winner of the election was:
  - Candidate Diana DeGette, who received 73.8% of the vote and 272,892 number of votes. 
 
## Challenge Overview
After delivering the results to the election commission, additional data was requested to complete the audit:
- The voter turnout for each county
- The percentage of votes from each county out of the total count
- The county with the highest turnout

### Election Audit Results
- **How many votes were cast in this congressional election?**
A total of 369,711 votes were cast in the election.

- **Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.**
  - The county of Jefferson cast a total of 38,855 votes, which is the 10.5% of the total votes.
  - The county of Denver cast a total of 306,055 votes, which is the 82.8% of the total votes.
  - The county of Araphoe cast a total of 24,801 votes, which is the 6.7% of the total votes.

- **Which county had the largest number of votes?**
Denver had the largest number of votes

- **Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.**
  - Candidate Charles Casper Stockham had 23% of the total votes, meaning he received 85,213 votes.
  - Candidate Diana DeGette had 73.8% of the total votes, meaning she received 272,892 votes.
  - Candidate Raymon Anthony Doane had 3.1% of the total votes, meaning he received 11,606 votes.

- **Which candidate won the election, what was their vote count, and what was their percentage of the total votes?**
Candidate Diana DeGette won the election with a total of 272,892 votes, reaching the 73.8% of the whole count. 

![election results](https://user-images.githubusercontent.com/104812189/180287637-7b35388a-c593-4d0f-8ebf-fede0587a7e5.PNG)

## Election Audit Summary
 Using this script, the election commission will be able to analyze future elections in order to get the same type of information we gathered, no matter the number of candidates, the number of counties, or the number of votes. 
 Some modifications might be necessary, here are two examples on where the code may change:
 1) The variable from the file we are analyzing, the path to load the file won't be the same in all elections.
 2) The variable from the file we are adding text to, the path from this file won't be the same in all elections. 
 
 ![variables modificables](https://user-images.githubusercontent.com/104812189/180287391-725efed3-bb82-47c1-9c40-94dfacc1f77c.PNG)

 Taking these modifications into account will be very useful for future analyzes. 
