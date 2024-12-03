# Valorant News Web Scraping 📰🎮

This project is a web scraping tool designed to collect the latest news and updates about the popular game Valorant from targeted websites. The tool extracts relevant data, such as headlines, summaries, publication dates, and associated images, and stores the information in a structured CSV file.

## Demo Video 
This is the Youtube video link to my Project : [https://youtu.be/Svoe94IImpQ?si=G8llcb32bue6nEMg]

## Features
1) Extracts the latest news headlines, summaries, images, and timestamps from Valorant-related news sections.
2) Saves the scraped data in a CSV format for easy analysis and usage.
3) Handles HTML parsing and dynamic elements with ease.

## Technologies Used
Python: Programming language.
Libraries:
a) requests: For sending HTTP requests to fetch webpage content.
b) BeautifulSoup (from bs4): For parsing and navigating HTML content.
c) csv: For saving data into a CSV file.

## Project Structure

Valorant-News-Web-Scraping/
├── valo_news_scraper.py   # Main Python script
├── valo_news.csv          # Output CSV file (after running the script)
└── README.md              # Project documentation

## Setup and Usage
### Prerequisites
a) Python 3.x installed on your system.

b) Install the required libraries by running: pip install requests beautifulsoup4

## Steps to Run
1) Clone this repository or download the script:
git clone https://github.com/shobhabagleinfeno/Valorant_News_Web_Scrapping.git

cd Valorant-News-Web-Scraping

2) Run the scraper script:
python valo_news_scraper.py

3) After execution, the scraped data will be saved in a file named valo_news.csv.

## How It Works
### Web Scraping:
The script sends a request to the target website to fetch its HTML content.
### Data Extraction:
The BeautifulSoup library is used to parse the HTML and extract news-related elements like titles, timestamps, and images.
### Data Storage:
The extracted data is formatted into a structured dictionary and saved into a CSV file.

## Output
The CSV file will contain the following columns:

1) Image
2) Title
3) Date
4) Headline
5) Summary
