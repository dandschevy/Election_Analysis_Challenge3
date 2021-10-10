# Election_Analysis_Challenge3

## Overview/Purpose
The subject of Module 3 was coding in Python using for loops and conditional statements with membership and logical operators.  In this module, Python code was used to analyze a csv file and audit a fictional election.  This included providing the total votes cast, the percentage and number of votes for each candidate, and the winning candidate, vote count, and percentage.  These election results were displayed on the terminal screen and printed to a separate text file.  The purpose of the Module 3 Challege was to add supplemental code in order to show the following additional results; 1.  The voter turnout for each county; 2.  The percentage of votes from each county out of the total count; 3.  The county with the highest turnout.  The output of the supplemental code above was also to be displayed on the terminal screen as well as added to the text file.

## Results and Summary

### Results 
The election data was analyzed and the following results were obtained:
  1.  Total election votes were 369,711
  2.  Jefferson County had 38,855 votes (10.5%), Denver County had 306,055 votes (82.8%), and Arapahoe County had 24,801 votes (6.7%)
  3.  Denver County had the largest turnout with almost 83% of the total
  4.  Charles Casper Stockham received 85,213 votes (23.0%), Diana DeGette received 272,892 votes (73.8%), and Raymon Anthony Doane received 11,606 votes (3.1%)
  5.  Based on the results in #4 above, Diana DeGette was the winner of the election with 272,892 votes and 73.8%

A report of the election results has been included in the analysis folder and can be accessed using the following link: https://github.com/dandschevy/Election_Analysis_Challenge3/blob/main/analysis/election_analysis.txt  

Additionally, an image of the election results can also be found below:
![PyPoll_Challenge_Terminal](https://user-images.githubusercontent.com/90434559/136714841-3168a242-80d1-4cd7-979a-10203ffe64c7.png)

### Summary

The election analysis Python code made analyzing the results of the election incredibly quick and efficient; more efficient than analyzing this data using Excel and pivot tables or VBA.  Also, due to the user-centric nature of Python coding, this script can be used for additional elections with very few modifications.  This is not an option when using pivot tables and there are size limitations in Excel when using VBA macros.  

The minor Python coding modifications, required for use in multiple elections, would be as follows:

  1.  With each new election, csv file name and file location would need to be updated in line #9 (file to load variable)
  2.  The resulting text file and folder would need to be updated in line #11 (file to save variable)
    
With these simple modifications, any elections csv file could be analyzed in seconds, with the results almost immediately available on the terminal screen and in a separate text file.  A link to the Python code can be found here for your review: 



