# Py Me Up, Charlie: Python Challenges

## Background

Both of these challenges encompasses a real-world situation where your Python scripting skills can come in handy. These challenges are far from easy so I see some hard work ahead!

## PyBank

* In this challenge, I was tasked with creating a Python script for analyzing the financial records of a company. I was given a set of financial data called [budget_data.csv](PyBank/Resources/budget_data.csv). The dataset was composed of two columns: `Date` and `Profit/Losses`. (Thankfully, the company had rather lax standards for accounting so the records were simple.)

* I created a Python script that analyzed the records to calculate each of the following:

  * The total number of months included in the dataset

  * The net total amount of "Profit/Losses" over the entire period

  * The average of the changes in "Profit/Losses" over the entire period

  * The greatest increase in profits (date and amount) over the entire period

  * The greatest decrease in losses (date and amount) over the entire period

* This is how the final output for the analysis look similar:

  ```text
  Financial Analysis
  ----------------------------
  Total Months: 86
  Total: $38382578
  Average  Change: $-2315.12
  Greatest Increase in Profits: Feb-2012 ($1926159)
  Greatest Decrease in Profits: Sep-2013 ($-2196167)
  ```

## PyPoll

* In this challenge, I was tasked with helping a small, rural town modernize its vote counting process.

* I was given a set of poll data called [election_data.csv](PyPoll/Resources/election_data.csv). The dataset is composed of three columns: `Voter ID`, `County`, and `Candidate`. My task was to create a Python script that analyzes the votes and calculates each of the following:

  * The total number of votes cast

  * A complete list of candidates who received votes

  * The percentage of votes each candidate won

  * The total number of votes each candidate won

  * The winner of the election based on popular vote.

* This is how the final output look similar:

  ```text
  Election Results
  -------------------------
  Total Votes: 3521001
  -------------------------
  Khan: 63.000% (2218231)
  Correy: 20.000% (704200)
  Li: 14.000% (492940)
  O'Tooley: 3.000% (105630)
  -------------------------
  Winner: Khan
  -------------------------
  ```

Do you need to solve a similar problem? Find out more about the solution by checking the files in this repository.

Reach out to me with any questions at maercoli@hotmail.com.

Warm regards,
Marina Ercoli
