# Election Analysis

## Overview of the project

The current project was made with the main objective of assisting Tom, a Colorado board of elections employee for an election audit of the results for congressional precinct of the mentioned US state. 

We worked to report the results for the following data:
1. Total number of votes cast.
2. Total number of votes for each candidate.
3. Percentage of votes for each candidate.
4. Winner of the election based on the popular vote.

In order to automate this process, we used Python, this way, we will be able to reuse the code for other kind of elections, as congressional, local and senatorial districts. 

The data was taken from three different sources of voting methods:
1. Ail-in ballots; are hand counted at the central office. 
2. Punch cards; are collected and then a machine tabulates votes to send the results to the central office. 
3. Direct recording electronic; the memory cards from DRE counting machines are sent to the central office and read by a computer. 

After explaining this, we can move forward to present the analysis. 


## Results 

* The total of votes for this congressional election were 369,711.

* Breakdown of the number of votes and the percentage of total votes for each county in the precinct.
  > Jefferson: 38,855 votes (10.5%).
  > 
  > Denver: 306,055 votes (82.8%).
  > 
  > Arapahoe: 24,801 votes (6.7%).

* The county with the largest number of votes was Denver. 

* Breakdown of the number of votes and the percentage of the total votes each candidate received.
  >Charles Casper Stockham: 85,213 votes (23.0%).
  >
  >Diana DeGette: 272,892 votes (73.8%).
  >
  >Raymon Anthony Doane: 11,606 votes (3.1%).

* The winner of this election was Diana DeGette, with 272,892 votes and a 73.8% out of 100%.


<img width="299" alt="election_analysis" src="https://user-images.githubusercontent.com/113856917/196604602-735be5fe-3b97-4f1b-a960-2d92839762f2.png">



## Election and Audit

### Summary 

As we said at the beggining, the script that we performed in Python, can be used for any elections with the appropriate modifications. 

The present script can be modified so it can be used in other elections:
- Instead of county we could look for states, regions, countries.
- Instead of candidate names, we could add a function so we know in which political party are the candidates. 

Talking about the greatest benefit of using this over the next elections is that the results can be reported and published in a faster and less complicated way. 

In general, some of the advantages of reusing code are save time and resources, as well as reduce redundancy. Something worth to mention is that it can be used on any operating machine, system, or platform, so it makes it easier to run the code in any place of work where is necesary. 



