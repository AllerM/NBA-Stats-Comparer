# NBA-Stats-Comparer
NBA Player Accolades and Stats Comparison Tool
Overview
This project is designed to provide users with a convenient way to compare the accolades and statistics of NBA players throughout history. By utilizing a web scraping script and a free NBA API, I gathered comprehensive data on all NBA players.

Features
Accolades Comparison: I selected eight of the most important accolades in NBA history to provide users with a quick and easy way to assess player achievements.

GOAT Score (Greatest Of All Time): To make player comparisons more intuitive, I developed the GOAT Score, a numerical representation of a player's dominance in their respective accolades. This score ranges from 0 to 100, with a higher score indicating a more accomplished player.

Accolades Included
The eight accolades we've chosen to highlight are:

Points Per Game
MVP Awards
NBA Championships
All-Star Selections
All-NBA Team Selections
All-Defensive Team Selections
Scoring Titles
NBA Finals MVP Awards

Calculating the GOAT Score
I designed a simple yet effective formula to calculate the GOAT Score for each player. The formula takes into account a player's number of accolades in each category and divides it by the current record for that accolade. For instance, if a player has 5 Scoring Titles and the current record is 10, their Scoring Titles attribute contributes to their GOAT Score as (5 / 10).

