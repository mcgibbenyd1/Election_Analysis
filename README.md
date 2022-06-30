# Election_Analysis

## Project Overview
A Colorado Board of Elections employee has given you the following tasks to complete the election audit of a recent local congressional election.

1. Calculate the total number of votes cast.
2. Get a complete list of candidates who received votes.
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.

## Resources
- Data Source: election_results.csv
- Software: Python 3.7.6, Visual Studio Code, 1.68.1

## Summary
The analysis of the election show that:
- There were 369,711 votes cast in the election.
- The candidates were:
  -Charles Casper Stockham
  -Diana DeGette
  -Raymon Anthony Doane
- The candidate results were: 
  - Charles Casper Stockham received 23.0% of the vote or 85,213 votes.
  - Diana DeGette received 73.8% of the vote or 272,892 votes.
  - Raymon Anthony Doane received 3.1% of the vote and 11,606 votes.
-The winner of the election was: 
  - Diana DeGette, who received 73.8% of the vote or 272,892 votes.

## Challenge Overview
Along with the initial information request for completing the election audit, the election commission has requested some additional data.

1. Calculate the total voter turnout for each county.
2. Calculate the percentage of votes from each county from the total vote count.
3. Determine the county with the highest number of voter turnout

## Challenge Summary
The analysis of this election data indicates:
- There were voters from 3 different counties invovled in the election:
  - Jefferson county voters contributed to 10.5% of the votes or 38,855 votes.
  - Denver county voters contributed to 82.8% of the votes or 306,055 votes.
  - Arapahoe county voters contributed to 6.7% of the votes or 24,801 votes.
- The county with the largest voter turnout was:
   - Denver county, whose voters contributed to 82.8% of the votes or 306,055 votes
   
The information compiled for the election commission can be output straight to the terminal window or to a text file. Below is the example of the terminal window output from the election data. 
   
<img src="https://github.com/mcgibbenyd1/Election_Analysis/blob/main/Election_Analysis_Terminal.png"   width="450" height="500" />

The python script written for this election analysis was written in a way that the output is in a templated form with the results displaying similar to the terminal above. Any CSV file containing election results and organized as "Ballot ID", "County" and "Candidate" can be used with the presented script as is. In order to modify the script in order to be used for any election could be:
   1. Make the Output text to be dynamic based on the headers in the CSV file with the results always calulating the total votes for a single column, percentage of each object under the header, and the largest/winner of the votes in a given column. 
   2. Checks, using if statements, could be added into the script for the possibility of computation of additional columns without needing to update the script to handle it. The could be done simply by checking to see if any value is present in a column before continuing through the template script. 
