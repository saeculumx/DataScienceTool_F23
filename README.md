CS:GO Match Data Analysis
Overview
This data set contains detailed information about professional Counter-Strike: Global Offensive (CS:GO) matches. It includes player performances, team dynamics, match outcomes, and various other metrics critical for analyzing and understanding competitive CS:GO play.
https://www.kaggle.com/datasets/mateusdmachado/csgo-professional-matches/data
Download and unzip them into data folder

Data Set Structure
The data set is comprised of several files, each focusing on different aspects of the matches:

Players.csv: Contains individual player performance metrics per match.

Columns: player_name, match_id, kills, deaths, assists, rating, etc.
Matches.csv: Details about each match, including teams, event, and final scores.

Columns: match_id, date, team_1, team_2, event_id, map_wins_1, map_wins_2, match_winner, etc.
Events.csv: Information about the events/tournaments the matches were part of.

Columns: event_id, event_name, location, prize_pool, teams_participated, etc.
Economy.csv: Round-by-round economic data for each team in the matches.

Columns: match_id, round, team_1_money, team_2_money, team_1_weaponry_value, team_2_weaponry_value, etc.
Maps.csv: Details of the maps played in each match.

Columns: match_id, map_name, team_1_score, team_2_score, map_winner, etc.

This data set is ideal for:

Statistical analysis of player and team performances.
Machine learning models to predict match outcomes.
In-depth understanding of gameplay strategies and economic decisions.
Analyzing the impact of different maps on match results.