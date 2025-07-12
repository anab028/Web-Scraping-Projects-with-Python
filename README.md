# 🕸️ Web Scraping & API Data Projects (Python + Pandas)

This repository showcases two beginner-to-intermediate level data projects using Python — one with HTML scraping and another with public API calls. The data is processed with Pandas and saved to CSV for further use.

---

## 📘 Project 1: Book Price Scraper (BeautifulSoup)

Scrapes book titles and prices from [books.toscrape.com](https://books.toscrape.com), a demo website designed for practicing web scraping.

### 🔹 Features
- Scrapes book titles and prices across multiple pages
- Uses BeautifulSoup and requests
- Cleans and structures data with Pandas
- Exports to CSV
- Optional: Matplotlib chart for price distribution

### 🔹 Technologies
- Python
- BeautifulSoup
- requests
- pandas
- matplotlib (optional)

### 🔹 Output
- `scraped_books.csv` — clean dataset of books and prices

---

## 💰 Project 2: Crypto Price Tracker (CoinGecko API)

Uses the [CoinGecko API](https://www.coingecko.com/en/api) to fetch real-time prices, market cap, and 24h % change for the top 20 cryptocurrencies.

### 🔹 Features
- No scraping — uses a JSON API (faster and more reliable)
- Extracts name, symbol, price, market cap, and 24h % change
- Saves to CSV
- Visualizes top 10 coins by price

### 🔹 Technologies
- Python
- requests
- pandas
- matplotlib

### 🔹 Output
- `top_20_crypto.csv` — updated crypto price dataset

---

## 🚀 How to Run

### 1. Clone the Repo
```bash
git clone https://github.com/your-username/web-scraping-and-api-projects.git
cd web-scraping-and-api-projects
