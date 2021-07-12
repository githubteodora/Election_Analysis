# Election Analysis
## Project overview
The code for this project is written in python 3. It uses the csv and os python packages, as well as loops (while, for), logical operators, dictionaries, etc. The goal of the project was to automate the analysis of election results, producing a summary of the results, recorded as a separate txt file.
This project also helps demonstrate the Visual Studio Code -> GitHub syn process via GitBash (on Windows).

## Methodology
1. Caludate the total number of votes cast.
2. Get a complete list of candidates who received votes (disctinct names).
3. Calculate the total number of votes each candidate received.
4. Calculate the percentage of votes each candidate won.
5. Determine the winner of the election based on popular vote.
6. Analyze the vote per county.

## Resources
 - data source: election_results.csv
 - Software: Python 3.7.6, Visual Studio Code 1.58.0
 - Screen capture of the terminal: 
---
 ![image](https://github.com/githubteodora/Election_Analysis/blob/main/Resources/terminal.PNG)
---
## Summary
1. The analysis of the election shows that there were 369,711 votes cast in the election
2. There were 3 counties where the election tool place, the vote distribution per county was as follows:
 - Jefferson: 10.5% (38,855)
 - Denver: 82.8% (306,055) --> largest number of votes
 - Arapahoe: 6.7% (24,801)
3. The candidates were: 
 - Charles Casper Stockham: won 23.0% (85,213 votes)
 - Diana DeGette: won 73.8% (272,892 votes)
 - Raymon Anthony Doane: won 3.1% (11,606 votes)
4. The winner of the election was Diana DeGette

## Challenge overview
The challenge was to develop code that counts votes per candidate and county, finds the candidate and county with the biggest number of votes and prints the result into a txt file. 

## Challenge summary
The developed code can be used for automating analyses of data in spreadsheets with hundreds of thousands of rows. The code heavily relies on clean data in order to produce a reliable output. The code automatically detects unique values in a column (i.e. candidate names, counties), counts occurances per value and produces a result by pulling the aggregared numbers from a python dictionary. The code also provides a way to add a summary analysis into a separate text file. The code can be reused for any analysis that requires repetitive counting of units for any number of distinct elements in an array. With minor adjustments, the code will also be able to sum values, or compare final results per element and classify the elements.
