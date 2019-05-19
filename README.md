# MLB_Statcast


# HOW TO RUN

- Download repository to local drive.
- Run the fixing statcast data file first.
- Run part_2 to create database. Password needs to be added. Also, PATH might need to be changed for MySQL database location. Code works for MySQL--root, localhost:3306, personal password.
- Run all the lines from the SQL script located in sql_db_script.txt that is in this repository.
- Export 2018_MLB_batters table from MySQL into a csv and place inside respository. My data is in repository and is named "2018_mlb_batters.csv".


# Does pitch velocity or ball spin rate from pitcher effect a batter's exit velocity?

- https://public.tableau.com/profile/chris.mcgee#!/vizhome/exit_velo_pitch_speed/Sheet1?publish=yes

# Barrels Visualization

- https://public.tableau.com/profile/chris.mcgee#!/vizhome/barrel_visualization/Sheet1?publish=yes

(*NOTE) bat_id_clean.csv is the clean version of bat_id.csv that is created after running fixing_all_pitches.ipynb. I used excel to clean the data. List of prblems include: 1 ID was missing. Names like J.D. Martinez showed up as firstname = J., last_name = D.. Also a few players had 3 names which will be a problem when using Fangraphs data later on in analysis.
