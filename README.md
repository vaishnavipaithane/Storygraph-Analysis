# Storygraph Reading Analysis
## Overview
This project analyzes my reading habits from August 2016 to March 2025 using data exported from StoryGraph. I cleaned the dataset using Python (Pandas) and visualized key insights in Power BI.
## Data Source
* The dataset was exported from StoryGraph and processed in Python before being imported into Power BI
* The cleaned dataset is stored as storygraph_cleaned.csv
## Data Cleaning & Processing
* Removed unnecessary columns with missing or irrelevant data
* Filled missing star ratings for read books with 0 (not rated)
* Converted 'Last Date Read' into a structured datetime format
* Extracted 'Year Read' from the date column for better trend analysis
