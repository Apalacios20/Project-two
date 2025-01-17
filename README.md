# Project-two

## **PROPOSAL**:
We’re looking to provide data to display the economic effect of covid on a major league sport, in this case, the MLB.  The timeline will be from 2019-2021 which will present each team’s league standing before, during, and through the recovery of 2020.  In a review of the data, we will be able to depict which teams were hit the hardest and what effect it had on players' performance if any.  It would also be of use to any sports enthusiast who would like to crunch stats and see what contributed to each team’s success in each of the years.


## Team Members: <br>
Osamu Adler -- Sergio Basurto -- Michael Diaz -- Anthony Palacios



## Data:
http://www.stevetheump.com/Payrolls.htm

https://www.espn.com/mlb/attendance/_/year/2021

https://www.espn.com/mlb/stats/player/_/view/batting/season/2021/seasontype/2/table/batting/sort/homeRuns/dir/desc



## Process:
### Extract:
Libraries used to extract data were Pandas and Splinter.

### Transform:
-Pandas: Extract tables from sources and editeas seen in the scraping code.  
-Splinter: There were some difficulties in the extraction, specifically with the name column for multiple sources due to the player name mashed with the team abbreviation.  Therefore, splinter was used to find the XPath of the desired data being "Player Name" and "Team Abbreviation".

### Load:
Exported Pandas data frames to CSV files, then imported into a relational database.  The database can tell you whatever it is you would like to know in the years 2019-2021 ranging from the Best Performing Player in many stat categories to the Best Performing Team.  Most importantly, you will see the effects of covid from year to year for both players and teams.



