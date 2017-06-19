# FredApi

Build a simple application for pulling and storing different kinds of macroeconomic data using the Federal Reserve's FRED API.  The FRED API provides a RESTful means of accessing many datasets published by the Federal Reserve - unemployment rates, interest rates, GDP, etc.  The data are modeled as "series" of "observations" with each observation having a date and value.  For more details on the API and datasets, visit https://research.stlouisfed.org/docs/api/fred/.  The endpoint you will be most interested in is fred/series/observations, so you may want to read the docs for that one in particular. 

Requirements:
- Your application should fetch the following FRED series in their entirety
    - Real Gross Domestic Product (GDPC1)
    - University of Michigan Consumer Sentiment Index (UMCSENT)
    - US Civilian Unemployment Rate (UNRATE)
- Your application should store the observations in a relational database running on localhost.
