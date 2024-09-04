# SQLAlchemy challenge

                                  Part 1: Analyze and Explore the Climate Data


Use the SQLAlchemy create_engine() function to connect to your SQLite database (1 point)

Use the SQLAlchemy automap_base() function to reflect your tables into classes (3 points)

Save references to the classes named station and measurement (4 points)

Link Python to the database by creating a SQLAlchemy session (1 point)

Close your session at the end of your notebook (1 point)

## **Precipitation Analysis**

Create a query that finds the most recent date in the dataset (8/23/2017) (2 points)

Create a query that collects only the date and precipitation for the last year of data without passing the date as a variable (4 points)

Save the query results to a Pandas DataFrame to create date and precipitation columns (2 points)

Sort the DataFrame by date (2 points)

Plot the results by using the DataFrame plot method with date as the x and precipitation as the y variables (4 points)

Use Pandas to print the summary statistics for the precipitation data (2 points)

## **Station Analysis**

Design a query that correctly finds the number of stations in the dataset (9) (2 points)

Design a query that correctly lists the stations and observation counts in descending order and finds the most active station (USC00519281) (2 points)

Design a query that correctly finds the min, max, and average temperatures for the most active station (USC00519281) (3 points)

Design a query to get the previous 12 months of temperature observation (TOBS) data that filters by the station that has the greatest number of observations (3 points)

Save the query results to a Pandas DataFrame (2 points)

Correctly plot a histogram with bins=12 for the last year of data using tobs as the column to count. (4 points)

                                       Part 2: Design Your Climate App

/

Start at the homepage.

List all the available routes.

/api/v1.0/precipitation

Convert the query results from your precipitation analysis (i.e. retrieve only the last 12 months of data) to a dictionary using date as the key and prcp as the value.

Return the JSON representation of your dictionary.

/api/v1.0/stations

Return a JSON list of stations from the dataset.
/api/v1.0/tobs

Query the dates and temperature observations of the most-active station for the previous year of data.

Return a JSON list of temperature observations for the previous year.

/api/v1.0/<start> and /api/v1.0/<start>/<end>

Return a JSON list of the minimum temperature, the average temperature, and the maximum temperature for a specified start or start-end range.

For a specified start, calculate TMIN, TAVG, and TMAX for all the dates greater than or equal to the start date.

For a specified start date and end date, calculate TMIN, TAVG, and TMAX for the dates from the start date to the end date, inclusive.






