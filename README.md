# Election_Analysis
## Overview of Election Audit
An election audit of a recent local congressional election was completed for the Colorado Board of Elections.
Following were the tasks that were performed during the process -
1. Calculated the total number of votes cast.
2. Getting total votes cast for each county that participated.
3. Finding the percentage of the votes for each of the counties found in 2.
4. Finding out the county with the largest turnout of votes.
5. Get a complete list of candidates who received the votes.
6. Calculate the total number of votes each candidate received.
7. Calculate the percentage of votes each candidate received.
8. Finding the Winning candidate's name
9. Finding the total winning count of votes for the winner
10. Based on 6. Finding the winning percentage of votes based on the total casted votes.

## Resources
- Data Source: election_results.csv
- Software: Python 3.8.5 , Visual Studio Code - Version: 1.66.2 (Universal)

## Summary

* The analysis of the election was shown at two different levels -
-  County Level
-  Candidate Level

### Results at County Level
    * Jeffereson had 10.5% of total votes casted i.e about 38,855 votes.
    * Denver had 82.8% of total votes casted i.e about 272,892 votes.
    * Arapahoe had 3.1% of total votes casted i.e about 24,801 votes.
    
#### County with largest turnout.
Denver had the largest turnout with a maximum number of votes being cast amounting to 272,892 votes i.e about 82.8%.

Code Snippet showing the logic for the county-wise votes and individual percentage, winning county, and how we print the result in the terminal and write that output to a txt file.
   
<img width="1142" alt="Votes_county_wise" src="https://user-images.githubusercontent.com/98556229/167273684-5fe9c38a-f4eb-470f-9b4e-1c14bb26cd22.png">

          
### Summary at Candidate Level
The Candidates were 
-   Charles Casper Stockham
-   Diana DeGette
-   Raymon Anthony Doane

### The candidate results were: 
-   Charles Casper Stockham received 23.0% of the vote and 85,213 votes.
-   Diana DeGette received 73.8% of the vote and 272,892 votes.
-   Raymon Anthony Doane received 3.1% of the vote and 11,606 votes

### Winner of Election:
    Diana DeGette was the winner of the election she received 73.8% of the vote and 272,892 votes.

Code Snippet showing the logic for the candidate-wise votes, winning candidate votes and individual & winning percentage, winning candidate, and how we print the result in the terminal and write that output to a text file.

<img width="1119" alt="Votes_candidate_wise" src="https://user-images.githubusercontent.com/98556229/167273711-8b9b471f-20a9-4c83-9fa1-975e8aaee145.png">

The election results were saved in txt file as follows :

![Election_analysis](https://user-images.githubusercontent.com/98556229/167273700-1ca8389e-e0c9-4638-8ae6-5f11afefa22a.png)


## Election Audit Summary
- The Python code used for the Election audit for congressional elections in Colorado state is powerful and robust. It can be re-used for a much wider scale.
For example:
    1. It can be reused for a larger data set, for more or all counties in the state, or even for all-states congressional election audits.
    2. If we want to know the county-wise winner, we can modify our python code to find the number of votes cast for each candidate in a county and evaluate their performances.
