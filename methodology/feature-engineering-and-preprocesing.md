## Engineered Features:
  - **season_start** - the beginning year of a season; helps for chronologically sorting observations
  - **season_end** - the end year of a season; helps for eventual year-based splitting and iterative forecasting
  - **next_season_ppg** - an NBA player's points per game for the following season (shifted forward by one year); becomes our label

## Preprocessing: 
 1. Create the new features listed above
 2. Drop all rows that have a missing label
 3. Sort by player name and then sort by season years for that player; ensures players' ppg stats are right beside their next_season_ppg



