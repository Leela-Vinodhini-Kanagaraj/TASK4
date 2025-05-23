# 🇮🇳 India Sports Rankings Web Scraper

This Python script scrapes sports ranking data from [FanRank.org](https://www.fanrank.org/) for Indian sports, across multiple paginated pages. The collected data is saved into an Excel spreadsheet for further analysis or reporting.

##  Features

- Scrapes sports rankings from 18 paginated web pages.
- Extracts data fields: **Sport**, **Format**, **Gender**, and **Rank**.
- Stores the collected data in a structured **Excel file**.
- Uses Python libraries: `requests`, `BeautifulSoup`, and `pandas`.

---

##  Requirements

- Python 3.7 or higher
- Required Python packages:
  - `requests`
  - `beautifulsoup4`
  - `pandas`
  - `openpyxl` (required for writing Excel files)

Install them using pip:

    pip install requests beautifulsoup4 pandas openpyxl

How to Run:

1.Clone this repository or download the script.

2.Run the script

      python india_sports_scraper.py
  
3.Once completed, the data will be saved as:

      Sports_rankings.xlsx


