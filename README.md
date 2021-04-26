# sqlalchemy-challenge

## Step 1 - Climate Analysis and Exploration

This homework assignment involved using Python and SQLAlchemy to do basic climate analysis and data exploration of the climate database. 

A starter notebook and hawaii.sqlite file was already provided to help complete the climate analysis and data exploration. 

### Precipitation Analysis
A query was designed to retrieve the last 12 months of precipitation data. The data was loaded into a Pandas DataFrame and the results were plotted with the DataFrame plot mathod. 

### Station Analysis
A query was designed to calculate the total number of stations and to find the most active station. Another query was than designed to retrieve the last 12 months of temperature observation data (TOBS). The results were then plotted as a histogram.

## Step 2 - Climate App
After completing the initial analysis, a Flask API was designed based on the queries developed. 

There were several routes available including information for :
- Precipitation on all dates
- List of stations
- TOBS information for the previous year
- List of the minimum temperature, the average temperature, and the max temperature for a given start date
- List of the minimum temperature, the average temperature, and the max temperature for a given start and end date

Flask jsonify was used to convert API data into valid JSON response objects.

