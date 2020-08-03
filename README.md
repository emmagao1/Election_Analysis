# Election_Analysis
## Overview of Election Audit
1) Calculate the number of votes cast
2) Get a complete list of candidates who received votes
3) Calculate the total number of votes each candidate received
4) Calculate the percentage of votes each candidate won
5) Determine the winner of the election based on popular vote


## Resources
Data Source: election_results.csv<br>
Software: Python 3.7.4, Visual Studio Code

## Election Audit Results
The analysis of the election shows that:<br>

There were 369, 711 votes in total. <br>

The number of votes and percentage of the total number of votes in each county were:

* Jefferson: 10.5% (38,855)
* Denver: 82.8% (306,055)
* Arapahoe: 6.7% (24,801)

The county with the largest number of votes was Denver with a total of 306,055 votes.

The Candidates were: <br>
* Charles Casper Stockham
* Diana DeGette
* Raymon Anthony Doane

The vote percentage and vote count each candidate received were:
* Charles Casper Stockham: 23.0% (85,213)
* Diana DeGette: 73.8% (272,892)
* Raymon Anthony Doane: 3.1% (11,606)

The winner of the election was:<br>
Diana DeGette, who received 73.8% of the vote and 272,892 number of votes

## Election Audit Summary

The script can be modified with an input statement where the user is being asked about the file name which then can be used in the os.path.join statement. Alternatively the election commission can save any new election under the same file name: election_results.csv and the script will give the results for the newest election.





