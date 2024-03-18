**Guide to files in this folder:**

"team-data.csv": Statistics for each NCAA D1 Men's Basketball team from 2008-2019 + 2022-2024. (2020-2021 excluded due to COVID-19 pandemic.)

"matchups.csv": Matchups within the March Madness tournament for all years of team-data.csv except 2024.

"training.csv": A fusion of team-data.csv and matchups.csv with randomized winners to compare data in each game for ML training/testing.

"matchups-YY-R#.csv": Matchups (or predicted matchups) for rounds (YY = year, # = 1-6 inclusive) of March Madness. Later rounds based on 3 model results for prior rounds. Code for the model draws from this and team-data.csv to predict.
