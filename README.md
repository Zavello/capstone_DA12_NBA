# NBA Rookie Advanced Analysis

A deep dive of an NBA rookies first year of the NBA was analyzed by advanced metrics. This data was used to determine if these advanced statistics are any indication of the rookie’s contribution to winning. Did the rookie have an immediate impact?

## Prerequisites

Before you begin, ensure you have met the following requirements:

* You have installed version 1.5.3 of Python

## Installing < NBA Rookie Advanced Analysis >

To install < NBA Rookie Advanced Analysis >, follow these steps:

Clone the repository 
git clone https://github.com/Zavello/capstone_DA12_NBA.git

## Usage

To install the basketball_reference_scrapper

```
pip install basketball_reference_scraper
```

To import the rookie draft class
```
from basketball_reference_scraper.drafts import get_draft_class

get_draft_class(YYYY)
```

To import player statistics
```
from basketball_reference_scraper.players import get_stats, get_game_logs, get_player_headshot

get_roster_stat(‘Team’,YYYY, data_format= ‘PER_GAME’, playoffs=False)
```
For ‘Team’ Use three letter team abbreviation found on https://www.basketball-reference.com/

For YYYY, use the year in which the season ended

Data_format=‘PER_GAME’ gives the stats in a per game format

Playoffs=False ignores statistics from playoff games that season.




## Contributing to < NBA Rookie Advanced Analysis >

To contribute to < NBA Rookie Advanced Analysis >, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.


## Contact

If you want to contact me you can reach me at <zechariahavello@gmail.com>.


