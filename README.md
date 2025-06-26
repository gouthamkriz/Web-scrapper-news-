# 📰 News Web Scraper

A Python-based project that automatically extracts news articles and related data from websites. The main goal is to collect structured information—such as headlines, publication dates, authors, and article content—from various news sources for analysis, aggregation, or monitoring.

---

## 👨‍💻 About the Developer

**Name**: Goutham Krishna C M  
**GitHub**: [gouthamkriz](https://github.com/gouthamkriz)  
**Role**: Aspiring AI Engineer passionate about building real-world data-driven applications.

---

## 🎯 Project Goal

To automate the extraction of structured news data from websites using Python, enabling efficient collection and analysis of current events and trends.

---

## 🚀 Features

- Extracts:
  - Headlines
  - Publication dates
  - Authors (if available)
  - Full article content
- Supports multiple news websites
- Saves data in CSV or JSON format
- Handles pagination and dynamic content (with optional Selenium)

---

## 🛠️ Tech Stack & Dependencies

- Python 3.x
- [`requests`](https://pypi.org/project/requests/) – for sending HTTP requests
- [`BeautifulSoup`](https://pypi.org/project/beautifulsoup4/) – for parsing HTML
- [`lxml`](https://pypi.org/project/lxml/) – fast HTML/XML parser
- [`pandas`](https://pypi.org/project/pandas/) – for saving and manipulating data
- *(Optional)* [`selenium`](https://pypi.org/project/selenium/) – for scraping JavaScript-rendered content

Install dependencies with:

```bash
pip install requests beautifulsoup4 lxml pandas
# Optional for dynamic sites:
pip install selenium
```

📦 How to Run the Project
- Clone the repository
git clone https://github.com/gouthamkriz/news-web-scraper.git
cd news-web-scraper
- Edit the script
- Open scraper.py and update the target URL and HTML tags/classes based on the news site you want to scrape.
- Run the scraper
python scraper.py
- 
### Output
- Extracted data will be saved as news_data.csv or news_data.json.
