# Election_Challenge #

## Overview of Election Audit:
The purpose of this election was to determine the results of the elction in 3 counties with 3 candidates. We had the full election data and used python scripts to generate an audit of the election results and analyze the winners at both the county and candidate level

## Election Audit Results: ##
[Commandline.png](https://github.com/mpournaras/Election_Challenge/blob/main/resources/election_analysis_command_line.png)

## Election Audit Summary ##

As we can see, we were able to take ~350,000 rows of voting data and quickly and efficiently retrieve results

I posit  to the election commission that this code could be easily used in 2 or more other situations:
1. Any other county/candidate combo could easily be read regardless of location or candidate name as this code uses indexes, lists, and dictionaries being run in a loop. As long as the data is formatted the same. If it is not, some small changes could be made to accomodate new row index locations for whatever data
2. Any number of votes in the voting data could be accomodated as well. Again, as long as the data is formatted in the CSV in a simialr fashion we could run the loop 10 times.... or even 10,000,000!

Both of these solutions are minimal work hours on the back end in the analysis phase. This is a very efficient way to analyze data and would be of benefitial use to any client public or private!
