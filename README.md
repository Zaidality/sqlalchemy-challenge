# sqlalchemy-challenge

Surfs_up

Weather analysis using SQLite and SQLAlchemy. Climate App building using Flask. Other tools include Python and Jupyter Notebooks.

Overview of Surfs Up Analysis

The purpose of this analysis is to review a dataset pertaining to weather conditions that has been stored in a SQLite database to do a climate analysis about Honolulu,Hawaii to help with a trip planning.

In order to explore the data in the SQLite database, we used SQLAlchemy to connect and generate queries to pull the necessary information needed for our analysis. Throughout this module, we used Jupiter notebook to import dependencies and create the commands to pull the data from the SQLite database.

We also used Visual Studio Code to create Python applications to share the results via a webpage by creating Flask routes and using Terminal to run the Flask app. When running the Flask app in Terminal, it generated the Flask routes in a web address http://127.0.0.1:5000 that could be shared.

<img width="1581" alt="ERD" src="https://github.com/Zaidality/sqlalchemy-challenge/assets/117491346/c0bd4754-d826-41c4-83e1-70d7e1488590">

Results

When we pulled the data, we first looked at the the precipitation for a one year timeframe. We reviewed the activity from August 23, 2016 - August 23, 2017. The average was 18% based on 2,021 observations. This tells us that throughout the year, Honolulu was mostly sunny throughout the day and experienced low rainfall.

![precipitation_stats](https://github.com/Zaidality/sqlalchemy-challenge/assets/117491346/b12da845-0d60-4b2b-8d7c-ed121481a950)

![precipitation_analysis](https://github.com/Zaidality/sqlalchemy-challenge/assets/117491346/cd06e1c0-337d-4298-bb70-9cfc5a179940)

We also looked at the number of weather stations that were actively collecting precipitation data and focus on one station that had the most observations recorded. In total, there were (9) stations with USC00519281 showing the highest amount of observations at 2,772 entries. We used the information from this station to review the temperature for the same time period. The results showed that the average temperature throughout the year was 72°F with a low of 54°F and a high of 85°F.
![temp_graph](https://github.com/Zaidality/sqlalchemy-challenge/assets/117491346/713af2b3-af91-4a0e-b11a-d06b6f451742)

Summary

In summary, the temperature in Honolulu is relatively the same throughout the year and the chances of continuous rainfall is low.

