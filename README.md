# 📚 BooksToScrape & QuotesToScrape - Web Scraping

## 📌 Overview
This project performs web scraping on [BooksToScrape](http://books.toscrape.com/) and [QuotesToScrape](http://quotes.toscrape.com/) using **BeautifulSoup**, **Requests**, and **Pandas**. The extracted data is cleaned and stored in structured formats for further analysis.

## 🛠 Technologies Used
- **Python** 🐍
- **BeautifulSoup** 🌐 (for parsing HTML)
- **Requests** 📡 (for making HTTP requests)
- **Pandas** 🏗 (for data handling and storage)

## 📈 Key Features
- Scrapes book details such as title, price, availability, and rating.
- Extracts quotes, authors, and tags from QuotesToScrape.
- Saves scraped data in structured formats like **CSV** and **JSON**.
- Implements error handling and request throttling to avoid getting blocked.

## 🚀 Getting Started
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/Magnus0969/BooksToScrape-Web-Scraping.git
cd BooksToScrape-Web-Scraping
```

### 2️⃣ Install Dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Run the Scraper
To scrape books data:
```bash
python scrape_books.py
```
To scrape quotes data:
```bash
python scrape_quotes.py
```

## 📂 Output
- Scraped book data is saved as `BooksToScrape.csv`.
- Scraped quote data is saved as `Quotes.csv`.

## 📝 Example Extracted Data
**BooksToScrape Sample Output:**
```
Title: "The Grand Design"
Price: £13.76
Availability: In Stock
Rating: 5 stars
```

**QuotesToScrape Sample Output:**
```
Quote: "The greatest glory in living lies not in never falling, but in rising every time we fall."
Author: Nelson Mandela
Tags: life, perseverance
```

## 📬 Contact
For any questions or collaborations, feel free to reach out on **[LinkedIn](https://www.linkedin.com/in/kmagadi/)**.

---
<p align="center">Made with ❤️ by Karthik B Magadi</p>
