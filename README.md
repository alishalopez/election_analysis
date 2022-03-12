# Election Analysis
## Overview of Election Audit
A Colorado Board of Elections employees need help to complete an audit with the following tasks of the recent local congressional election. 
 1. Calculate the total number of votes cast.
 2. Get a complete list of candidates who received votes.
 3. Calculate the total number of votes each candidate received.
 4. Calculate the percentage of votes each candidate won.
 5. Determine the winner of the election based on popular vote.
 6. Get a unique list of counties where voting occurred.
 7. Calculate the total number of votes from each county.
 8. Calculate the percentage of votes from each county.
 9. Determine which county had the largest voting turnout.
 
## Results
* 369,711 votes were cast in this congressional election.
* The county results of the precinct: 
  * Jefferson cast 10.51% of the vote, for 38,855 votes.
  * Denver cast 82.78% of the vote, for 306,055 votes.
  * Arapahoe cast 6.71% of the vote, for 24,801 votes.
* Denver had the largest number of votes.
* The candidate results were:
  * Charles Casper Stockham received 23.0% of the vote, for 85,213 votes.
  * Diana DeGette received 73.8% of the vote, for 272,892 votes.
  * Raymon Anthony Doane received 3.1% of the vote, for 11,606 votes.
* The winner of the election was Diana DeGette with 73.8% of the vote and 272,892 votes.

Using the following code, we were able to run through the data given and print out the winner, their vote count and winning percentage.

``` Python
    winning_candidate_summary = (
        f"-------------------------\n"
        f"Winner: {winning_candidate}\n"
        f"Winning Vote Count: {winning_count:,}\n"
        f"Winning Percentage: {winning_percentage:.1f}%\n"
        f"-------------------------\n")
    print(winning_candidate_summary)
```

Election Results as shown in text file:

![election_analysis](https://github.com/alishalopez/election_analysis/blob/245ea73f04fa54154d82102ba66267637394ca7f/resources/election_results.png)

## Summary
The election commission could easily use the python code provided to analyze data for elections in many years to come. They are able to find candidate names, county names, votes and percentage votes for each. This can be printed in the terminal or another text file for easy readability. This information is viable as it gives insight to voter turnout, trends and the winner of each election. 

Currently, the election_results.csv file is the file being analyzed through the code, but that can change for any election file they want to use later instead. Changing where the information is stored later can also be changed by creating a new text file. A file can be created to store each election year’s data and keep better organized if they want to look back at it later. They are even able to go more into depth and find the percentage of votes that went towards candidates within each county with a few alterations to the code.
