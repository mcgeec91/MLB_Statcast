# MLB_Statcast


# HOW TO RUN

- Download repository to local drive.
- Run the fixing statcast data file first.
- Run part_2 to create database. Password needs to be added. Also, PATH might need to be changed for MySQL database location. Code works for MySQL--root, localhost:3306, personal password.
(*NOTE) bat_id_clean.csv is the clean version of bat_id.csv that is created after running fixing_all_pitches.ipynb. 1 ID was missing and names like J.D. Martinez showed up as firstname = J., last_name = D.. Also a few players had 3 names which will be a problem when using Fangraphs data later on in analysis.
