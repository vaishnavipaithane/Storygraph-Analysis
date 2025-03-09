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
## Visualizations & Insights
In Power BI, I created the following insights:
1. Books Read Per Year – Trends in my reading over time.
2. Books Read Per Month – Monthly reading habits.
3. Books Read by Format – Paperback, digital, or audiobooks.
4. Most Read Authors – My most frequently read authors.
5. Books Read vs Star Ratings – How I rate books over time.
6. Average rating over the years.
## Future Improvements
* Analyze genre-based insights and audiobook lengths if available in future datasets
* Incorporate publication year trends to compare old vs. new books and publication date vs read date
