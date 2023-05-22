# nosql-challenge

## Project Introduction
The UK Food Standards Agency evaluates various establishments across the United Kingdom, and gives them a food hygiene rating. You've been contracted by the editors of a food magazine, Eat Safe, Love, to evaluate some of the ratings data in order to help their journalists and food critics decide where to focus future articles.
The data provided in the establishments.json file, stored in the resources folderfile can be imported using Terminal with mongoimport --type json -d uk_food -c establishments --drop --jsonArray establishments.json
## Contents
* The NoSQL_setup.ipynb sets up and updates the database. 
* The NoSQL_analysis.ipynb queries relevant information for analyses and converts results into Pandas DataFrame. 