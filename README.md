# sqlalchemy

## Honolulu Climate Analysis and Exploration

## Overview

This project conducts a detailed climate analysis and data exploration for Honolulu, Hawaii, using a comprehensive dataset stored in a SQLite database. It utilizes Python along with SQLAlchemy to interact with the database, Pandas for data manipulation, Matplotlib for data visualization, and Flask to create an API that serves the results.

## Project Structure

## Files
- climate_starter.ipynb: Jupyter Notebook for climate analysis and data exploration.
- hawaii.sqlite: SQLite database containing climate data for Honolulu.
- app.py: Flask application to serve the climate data via API endpoints.
## Part 1: Climate Analysis and Data Exploration
Using SQLAlchemy, this part involves:

- Connecting to the SQLite database.
- Reflecting tables into classes and creating a session.
- Performing precipitation and station analyses, including data queries for the most recent 12 months and plotting the results.
- Closing the session after analysis.
## Part 2: Climate App
Using Flask to create an API based on the queries developed in Part 1:

## Endpoints:
- /: Home page listing all routes.
- /api/v1.0/precipitation: Returns JSON of the last 12 months of precipitation data.
- /api/v1.0/stations: Returns JSON list of stations.
- /api/v1.0/tobs: Returns JSON list of temperature observations (TOBS) for the previous year from the most active station.
- /api/v1.0/<start> and /api/v1.0/<start>/<end>: Returns JSON list of the minimum, average, and maximum temperatures for a specified date range.
