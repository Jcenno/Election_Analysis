# Election_Analysis
## Overview of Election Audit
Seth and Tom have asked us to calculate various metrics and do analysis on a election_results.csv file they have provided. This analysis will be presented to the election commission. Specifically the election commission has asked for the vote turnout for each county, the percentage of votes from each county out of the total count, and the county with the highest turnout. Below I will demonstrate the methods I used to find the answer to the questions requested as well as my analysis of the results.
## Election-Audit Results:
- How many votes were cast in this congressional election?
  - Total Votes: 369,711

- We used a with statment to read and convert from the election_results.csv file to a list of dictionairies. We then used a for loop to count the number of votes as shown below.

![alt text](https://github.com/Jcenno/Election_Analysis/blob/5e395f5054f00a4cbe7f64504e03789b22f44407/Resources/Election%20Results.jpg)

- Here is a breakdown of the number of votes and the percentage of total votes for each county in the precinct. I have also shown the code I used to print this result to a text file.

![alt text](https://github.com/Jcenno/Election_Analysis/blob/3295dbcabba89f1ed4747330d7e5f669c97aecb5/Resources/County%20Votes.jpg)

- As we can see in the image above, Denver has the largest number of total votes.
  - The number of votes and the percentage of tatal votes each candidate recieved:
  Charles Casper Stockham: 23.0% (85,213)
  Diana DeGette: 73.8% (272,892)
  Raymon Anthony Doane: 3.1% (11,606)
  
- Looking at this data we can see that the winner is Diana DeGette with 272,892 votes (73.8% of the total vote). One thing to keep in mind is on line 129 we see that I needed to reset the winning_precentage variable back to 0.

![alt text](https://github.com/Jcenno/Election_Analysis/blob/a612c199bf5f504adda24a0d63d4c88c0512fd6e/Resources/Winning%20Percentage.jpg)

1. You could use the CSV file to find out how each candidate performed in each county.
2. We could create another field in the CSV file as a row to label party affiliation and then calculate the percentage of votes that went to each party.



  
