# SQLAlchemy_Challenge

I used Python and SQLAlchemy to do a climate analysis and data exploration of the climate database. All of the analysis are completed using SQLAlchemy ORM queries, Pandas, and Matplotlib.


# Reflect Tables into SQLAlchemy ORM
The analysis was done inside a jupyter notebook file. I used SQLAlchemy create_engine to connect to the sqlite database and then used SQLAlchemy automap_base() to reflect the tables into classes. References to those classes are saved as variables and are called Station and Measurement.

# Reflect Tables into SQLAlchemy ORM
The analysis was done inside a jupyter notebook file. I used SQLAlchemy create_engine to connect to the sqlite database and then used SQLAlchemy automap_base() to reflect the tables into classes. References to those classes are saved as variables and are called Station and Measurement.

After setting up the database, I did an analysis on the precipitation data. Specifically, I designed a query to retrieve the last 12 months of precipitation data. To do this, I used a package called dateutil.relativedelta to calculate the date 1 year ago from the last point in the database. I then stored the date and precipitation values from the query into a Pandas dataframe so that I could plot the results as a bar chart using Matplotlib.
