# ELECTION ANALYSIS
## PROJECT OVERVIEW
This Project involves auditing and reporting a local congressional election results in Colorado for the election commission. The commission requested to see the total number of votes cast per county, the complete list of candidates who received the votes, the percentage of votes for each county and candidate, the county with the highest turnout, and the winner of the election based on the popular vote. 

The analysis was carried on using a CSV file of collated data from the eletion and the sofware used was Python 3.9.12 and Visual studio Code -x64-1.70.2.


## ELECTION AUDIT RESULTS
The outcome of the Election analysis are as folllows;

### 1. TOTAL NUMBER OF CAST VOTE
### 369.711
![total vot](https://user-images.githubusercontent.com/109990578/187520695-405591f1-0ecd-41be-b339-de865cf6ec95.png)

![COUNT2](https://user-images.githubusercontent.com/109990578/187535071-2581bfc0-d759-48a9-b6dd-d4f10a0d3d6a.png)


### 2. BREAKDOWN OF THE NUMBER OF VOTES AND THE PERCENTAGE OF TOTAL VOTES PER COUNTY
-----------------------------------------------------
  COUNTY NAMES   |  VOTES  | PERCENTAGE OF TOTAL VOTES
-----------------|---------|---------------------------  
Jefferson        |  38,855 | 1.5%
Denver           | 306,055 | 82.8%
Arapahoe         |  24,801 | 6.7%
-------------------------------------------------------

![county v](https://user-images.githubusercontent.com/109990578/187527001-404597e1-59c5-4fa2-9161-4c68eb5fc4d4.png)

![PERCOUNTY](https://user-images.githubusercontent.com/109990578/187535441-b1c3bf50-ddc1-4abf-9def-6480a27c59d2.png)


### 3. COUNTY WITH LARGEST NUMBER OF VOTES
Denver has the largest number of votes with a total of **306,055(82.8%)**.

![county v](https://user-images.githubusercontent.com/109990578/187529877-021f29c2-f1ca-4837-b334-c989eeeec555.png)

![WINNING COUNTY](https://user-images.githubusercontent.com/109990578/187535772-c83fd196-3a19-449b-bb9b-f302c33f19d7.png)


### 4. BREAKDOWN OF THE NUMBER OF VOTES AND THE PERCENTAGE OF TOTAL VOTES RECEIVED BY EACH CANDIDATE
-----------------------------------------------------
 CANDIDATE NAMES |  VOTES  | PERCENTAGE OF TOTAL VOTES
-----------------|---------|---------------------------  
Charles Casper   |  85,213 | 23.0%
Diane DaGette    | 272,892 | 73.8%
Raymon A. Doane  |  11,606 | 3.1%
-------------------------------------------------------

![cand](https://user-images.githubusercontent.com/109990578/187528864-42eccdbb-94bd-45da-90a1-82a572d7aadf.png)

![CANDIDATE VOT](https://user-images.githubusercontent.com/109990578/187536379-8c7270e0-9794-4a2d-bfcd-555d9e873a4f.png)


### 5. WINNER
- NAME: **DIANE DEGATTE**
- WINNING VOTE COUNT: **272,892**
- PERCENTAGE OF TOTAL VOTES: **73.8%**

![WI](https://user-images.githubusercontent.com/109990578/187529449-5dac8c6d-7327-47c0-98e8-65ba1e42d584.png)

![WINNING CAND](https://user-images.githubusercontent.com/109990578/187536481-864f9902-af77-49d0-8b29-88a09dc10f45.png)

## ELECTION AUDIT SUMMARY

The following summarize the election results;

 The total number of votes = 369.711
 ------------------------------------------------------------------
 CANDIDATE NAMES |  VOTES    | PERCENTAGE OF TOTAL VOTES | POSITION
-----------------|-----------|---------------------------|--------- 
Charles Casper   |  85,213   | 23.0%                     | 2ND
**Diane DaGette**|**272,892**|**73.8%**                  |**IST**
Raymon A. Doane  |  11,606   | 3.1%                      | 3RD
-------------------------------------------------------------------
-----------------------------------------------------------------
  COUNTY NAMES   |  VOTES    | PERCENTAGE OF TOTAL VOTES | RATING
-----------------|---------  |---------------------------|--------        
Jefferson        |  38,855   | 1.5%                      | 3RD
**Denver**       |**306,055**|**82.8%**                  |**IST**
Arapahoe         |  24,801   | 6.7%                      | 2ND
-----------------------------------------------------------------
**WINNER:** DIAGNE DAGETTE With 272,892 (73.8%) Votes

**HIGHEST COUNTY:** DENVER With 306,055 (82.8%) Votes

                    
After exploiting different techniques to achieve an excellent results in this analysis, i will propose that python can be used for collating and analyzing the US presidential election by modifying this python script in the following ways;
- Creating a list of states and a dictionary for the votes of all the US states will enables the commision to determine the total votes, percentage of votes for all the states and total number of candidates.
- Using a for loops and if statement to narrow down the results particularly to candidate, state, and percentage for each of the states and candidate. 
This will be a good analytical way to collate and audit the US election results to declare a winner.


