# UK Food Establishments Analysis

This project analyzes food establishment data from the UK, focusing on hygiene scores, ratings, and local authority statistics. The data is sourced from a MongoDB database containing various collections related to food establishments.

## Project Overview

The main tasks completed in this assignment include:

1. **Database Connection**: Connected to the MongoDB instance containing the `uk_food` database.
  
2. **Data Queries**:
   - Counted establishments with a hygiene score of 20.
   - Found establishments located in London with a rating value of 4 or higher.
   - Searched for establishments with a rating value of 5 within a specified geographic range.
   - Analyzed establishments with a hygiene score of 0, grouped by local authority.

3. **Data Processing**:
   - Converted query results into Pandas DataFrames for easier analysis and manipulation.
   - Displayed relevant statistics and visualizations from the data.

4. **Aggregation Pipeline**: Created an aggregation pipeline to count establishments with a hygiene score of 0, grouped by local authority, and sorted the results.

