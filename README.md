# World Largest Banks ETL Pipeline

This project extracts the list of the largest banks from a Wikipedia snapshot, 
transforms their market capitalization values into multiple currencies, 
and loads the results into both a CSV file and a SQLite database.

---

## Features
- **Extract**: Scrapes Wikipedia data for the top banks by market capitalization.
- **Transform**: Converts market capitalization values into GBP, EUR, and INR using exchange rates.
- **Load**: Saves data into CSV and SQLite database.
- **Query**: Demonstrates example SQL queries on transformed data.
- **Logging**: Tracks ETL progress with timestamped logs.

---

## Technologies Used
- Python (BeautifulSoup, Requests, Pandas, NumPy, SQLite3)
- Wikipedia (Archived Snapshot)
- CSV & SQLite for storage

---
