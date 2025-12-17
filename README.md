# Author-Info-Checking-Bot
Python bot engineered to automate the extraction and structural parsing of author-specific metadata from the Reddit API. Demonstrates proficiency in data collection, cleaning, and social media data analysis.

## Project Goal and Context
The objective of this project was to automate the collection of author metadata from the Reddit platform, transforming unstructured social media data into a clean, structured format for downstream analysis. This addresses the manual and time-consuming process of gathering large volumes of user information for research or business intelligence purposes.

The final output is a reproducible data pipeline that connects to the Reddit API, extracts specified author attributes (e.g., karma, post history), and exports the results to a structured CSV file.

## Methodology & Implementation
The pipeline was built using Python, focusing on modularity and robustness:

* API Integration: Engineered a connection layer using the PRAW (Python Reddit API Wrapper) library to securely and efficiently retrieve data from Reddit based on specific search criteria (e.g., subreddit or post ID).   

* Data Extraction & Parsing: Developed logic to iterate through retrieved objects, extracting key metrics and metadata (e.g., account age, comment karma, number of submissions) for the author of each data point.   

* Data Transformation: Implemented a data cleaning and structuring module using the Pandas library to convert the raw, nested JSON/API response into a flat, tabular format (CSV), suitable for subsequent statistical analysis.

* Automation: The script was designed to run autonomously, demonstrating the ability to automate a complex, repetitive data collection task for real-world applications.

## Key Results and Accomplishments
* Efficiency: Successfully automated the data collection workflow, enabling the fast retrieval of thousands of author records, removing the need for manual data scraping.

* Data Integrity: The transformation module ensured data integrity by handling missing values and standardizing author attributes into a consistent, scannable dataset.

* Tool Proficiency: Demonstrated expertise in Python's ecosystem for data engineering, specifically handling large datasets and integrating third-party APIs.
