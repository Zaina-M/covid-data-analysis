COVID Cases and Vaccination Analysis

This project tracks and analyzes COVID-19 trends and vaccination data for Ghana and Nigeria.  
I fetch the data from public APIs, clean and organize it with pandas, visualize trends with matplotlib, and store the data in SQLite for easy querying.


## Features

- Fetches COVID-19 cases and vaccination data from APIs  
- Cleans and arranges data into tables (DataFrames) using pandas  
- Converts dates, merges tables, and handles cumulative & daily data  
- Visualizes trends over time for cases and vaccinations  
- Generates summary tables for total cases, total vaccinations, peak days, and averages  
- Stores data in SQLite for further analysis and querying  


## How to use
1. Open the Jupyter notebooks in Google Colab:
   - COVID_19_Trends_Tracker.ipynb (cases)  
   - COVID_19_Vaccination_Process_Tracker.ipynb (vaccinations)  
2. Run the cells step by step to fetch, analyze, and visualize data  
3. (Optional) If running locally, install the required libraries:
   bash
   pip install pandas matplotlib requests sqlalchemy

   ## Credits

Data fetched from public COVID-19 APIs.

License

MIT License

## About the Author

Hi! I’m Zainab , a student and data enthusiast.
This project was created to practice data fetching, cleaning, analysis, and visualization using Python, pandas, matplotlib, and SQLite.
It’s also a way to explore real-world COVID-19 data for Ghana and Nigeria.
