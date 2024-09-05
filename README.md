## Task 5: Web Scraping Program

### Overview

This Python program is designed to extract product information from an e-commerce website. The script scrapes key details such as product names, prices, and ratings, then stores the extracted data in a structured format, such as a CSV file, for easy analysis and further processing. This tool is useful for gathering market data, monitoring product trends, or simply automating data collection from online stores.

### Features

- **Product Information Extraction**: Scrapes essential details like product names, prices, and ratings from the target e-commerce site.
- **Data Structuring**: Organizes the extracted information into a CSV file, allowing for easy sorting, filtering, and analysis.
- **Customizable**: The program can be adapted to scrape additional fields or from different e-commerce platforms.
- **Error Handling**: Built-in mechanisms to handle exceptions like missing data, website changes, or connection issues.
- **Automation-Friendly**: Can be set up to run at specific intervals for regular data collection or integrated into larger data pipeline workflows.

### Requirements

- **Python 3.x**: The program is built using Python.
- **Libraries**: The following libraries are required for running the script:
  - `requests`: To send HTTP requests to the website.
  - `BeautifulSoup`: To parse the HTML content of the webpage.
  - `pandas`: To store the extracted data in a CSV format.
  - `csv`: (Optional) To manually work with CSV file creation.
