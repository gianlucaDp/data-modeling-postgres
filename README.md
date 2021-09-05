# Data Modeling with PostgreSQL
### Scope
The project scope is to extract data from different log files of songs and webpage usage to retrieve info about 
users, artists, songs, songs played and upload everything to a PostgreSQL database.
### Project content
The project consists of three python files, two Jupyter Notebook and a collection of log file:
* data : Folder tree contanining all the logs
* create_tables.py : Python script to drop (if already exist) and create the project SQL tables
* etl.py : Script to parse the log files and insert the data into the database
* etl.ipynb : Jupyter Notebook used to explore the data, helpful to create the queries
* test.ipynb : Jupyter Notebook to test the project, contains SELECT queries on the database