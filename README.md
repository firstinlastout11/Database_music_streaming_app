# Problem definition

A startup with a music streaming app service wants to analyze the data they have been collecting on 
songs and its user activities on the application. 
The data contains the information on what music its uers listened to and other information on the user, songs and artists.
Throughout this database, the company can have an easy access to the structured data on the needed information. 

# Database schema

In the database, the schema used to organize the data is the star schema. It has a fact table of songplays which contains information on the log data of song plays.
Then, it has 4 dimension tables: users, songs, artists and time.
Through this schema, the database is normalized and organized in such a way that its users can efficiently query the data.

# ETL pipeline

Regarding the ETL pipeline, the original data was in the form of JSON format. Using the Python backend, the database was organized in the above described star schema. 

# How to run the codes
Depending on the system, postgreSQL should be installed in the local machine. For Mac users, this link illustrates how to set up PostgreSQL on the machine: https://www.codementor.io/@engineerapart/getting-started-with-postgresql-on-mac-osx-are8jcopb.
After the installation, to run the code, create_table.py needs to be run.
For OS, simply type "python create_tables.py" at the terminal. After running the code, etl.py needs to be run by typing "python etl.py"


