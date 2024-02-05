# DS210-Project
The dataset used for this project includes all 380 English Premier League matches in the 2020-2021 football season. Each one of the 380 observations in this dataset is an individual match from the 2020-2021 season. There were more than 100 variables in the orginial 2020-2021 dataset, but for analysis purposes, the dataset was refined into a subset called **refined_epl** that only includes 24 variables of interest. The code for this subset is included in the markdown file. 

The data for the 2020-2021 season came from a larger kaggle dataset at https://www.kaggle.com/datasets/saife245/english-premier-league?resource=download

Full time and half time results came from TBWSport at http://www.tbwsport.com and Livescore at http://www.livescore.com

Match statistics came from Sportinglife, ESPN Soccer, Bundesliga.de, Gazzetta.it and Football.fr


| Variable                    |  Description
|:----------------|:--------------------------------
|`Div`                        | League Division
|`Date`                       | Match Date (dd/mm/yy)
|`Time`                       | Match Time (hh/mm/ss)
|`HomeTeam`                   | Home Team
|`AwayTeam`                   | Away Team
|`FTHG`                       | Full Time Home Goals
|`FTAG`                       | Full Time Away Goals
|`FTR`                        | Full Time Result
|`HTHG`                       | Half Time Home Goals
|`HTAG`                       | Half Time Away Goals
|`HTR`                        | Half Time Result
|`Referee`                    | Match Referee
|`HS`                         | Home Team Shots
|`AS`                         | Away Team Shots
|`HST`                        | Home Team Shots on Target
|`AST`                        | Away Team Shots on Target
|`HHW`                        | Home Team Hit Woodwork
|`AHW`                        | Away Team Hit Woodwork
|`HC`                         | Home Team Corners
|`AC`                         | Away Team Corners
|`HF`                         | Home Team Fouls Committed
|`AF`                         | Away Team Fouls Committed
|`HO`                         | Home Team Offsides
|`AO`                         | Away Team Offsides
|`HY`                         | Home Team Yellow Cards
|`AY`                         | Away Team Yellow Cards
|`HR`                         | Home Team Red Cards
|`AR`                         | Away Team Red Cards
|`NewDate`                    | Date of Match as date data type
|`Winner`                     | Winner of the match (home or away)
|`MoreRedCards`               | Club that ends the match with the most red cards
|`WinnerClub`                 | Name of club who won the match
|`TotalMatchReds`             | Total of red cards for both clubs during a match
|`TotalFouls`                 | Total number of fouls for both clubs during a match
|`HTScore01`                  | Half time score in 0 and 1 format for regression
|`FTScore01`                  | Full time score in 0 and 1 format for regression
|`Crowds`                     | Whether fans were present at the match or not present
|`TotalMatchYellows`          | Total number of yellow cards during an individual match
|`MoreYellowCards`            | Club that ends the match with the most yellow cards
|`MoreFouls`                  | Club that ends the match with the most fouls
|`PostInt`                    | Whether or not a match falls within a week of an international break
|`HalfTimeWinner`             | Who wins at halt time with values rewritten to be more readable
|`HomeShotsOnTarget`          | How many home club shots were on target
|`AwayShotsOnTarget`          | How many away club shots were on target


