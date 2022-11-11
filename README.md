# Election-Analysis

## Overview of Election Audit
A Colorado board of Elections employee gave me the task of completing an election audit for the recent local congressional election between Charles Casper Stockham, Diana DeGette, and Raymon Anthony Doane. Once the task was finished, they requested if I could go more into detail and include:
- The voter turnout for each county
- The percentage of votes from each county out of the total count 
- The county with the highest turnout

Of course, I said yes! I went back to work and included all of that information. Below is my work.

## Resources 
- Our main data source was an excel file: election_results.csv
- We used Python 3.7.6 and Visual Studio Code

## Election Audit Results
- How many votes were casted in this congressional election?

In this congressional election, there were a total of 369,711 votes

![Total Votes](https://github.com/jgarciat1/Election-Analysis/blob/main/total_votes_sc.png)

- Provide a breakdown of the number of votes and the percentage of total votes for each county in the precinct.

With the 369,711 total votes this election, they were distributed amongst the Denver, Jefferson, and Arapahoe counties as follows: 
1. Denver County had 306,055 votes or an 82.8% share
2. Jefferson County had 38,855 votes or a 10.5% share
3. Arapahoe County had 24,801 votes or a 6.7% share

![County Votes](https://github.com/jgarciat1/Election-Analysis/blob/main/county_votes_sc.png)

- Which county had the largest number of votes?

Denver County was the county with the largest number of votes as there were 306,055 votes, which was 82.8% of the total votes

- Provide a breakdown of the number of votes and the percentage of the total votes each candidate received.

Here are the results for the 3 candidates in this election:
1. Diana DeGette received 272,892 votes or 73.8% of the total
2. Charles Casper Stockham received 85,213 votes or 23.0% of the total
3. Raymon Anthony Doane received 11,606 votes or 3.1% of the total

![Candidate Results](https://github.com/jgarciat1/Election-Analysis/blob/main/candidate_results.png)

- Which candidate won the election, what was their vote count, and what was their percentage of the total votes?

Diana DeGette won the election by a large margin with a vote count of 272,892 votes, which was nearly 200,000 more votes than second place candidate Charles Casper Stockham. She took 73.8% of the total votes in this election

![Winner of Election](https://github.com/jgarciat1/Election-Analysis/blob/main/winner_of_election.png)

## Summary
The analysis of the election show that:
1. There were 369,711 total votes casted in the election
2. The main candidates were 
  - Charles Casper Stockham
  - Diana DeGette
  - Raymon Anthony Doane
3. The final voting results were:
  - Charles Casper Stockham received 23% of the votes with a total count of 85,213 votes
  - Diana DeGette received 73.8% of the votes with a total count of 272,892 votes
  - Raymon Anthony Doane received 3.1% of the votes with a total count of 11,606 votes
4. The winning candidate was Diana Degette, as she received over 73% of the votes

## Challenge Overview 
For this challenge we did the most coding we have done to date. We used the Excel CSV file and linked it to the Visual Studio Code application. There, we started by assigning variables and initializin the voter count. Once the variables were created, we used various formulas to have the excel do the work for us. We set conditionals to pull data in a specific manner and once everything was finalized, we printed the candidates results to the terminal. 

## Challenge Summary
This challenge was very hard. I ran into multiple issues were my file somehow disconnected from the VS Code and I had to mess with the applications and my file structure on my computer to get it to stay connected. I am not sure how that happened but finally I got it to work. Overall, the coding portion wasn't too hard, just very tedious. It took a lot of patience but once everything ran smoothly, it was rewarding. 

## Election-Audit Summary
#### In a summary statement, provide a business proposal to the election commission on how this script can be used—with some modifications—for any election. Give at least two examples of how this script can be modified to be used for other elections.

I would mention that the same work we did for this election can be copied onto other elections. All we need is the voting results as an excel. After that, we can alter the names of the candidates, counties, etc. 

Example 1: Update the file to the name of the county we are analyzing
Example 2: Update the file to the names of the candidates we are analyzing

Once this has been done, everything else just follows through as we did with the previous election. We can count the votes, do the calculations, and then analyze the final results. 
