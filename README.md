# Financial-Stock-Sentiment-Algorithm-

# eBay Data Collection Project 📊
Group 17: Aditya Satpute, Meghana S Kanthadai, Ian Heggen

## Project Overview 👀
This project aims to assess eBay's future stock performance by analyzing sentiment data collected through web scraping techniques. Contents from **Business Insider** and **Reddit's WallStreetBets subreddit** are scraped to gather investor sentiment. The data is then stored in MongoDB correlating public sentiment with eBay's stock price movements.

## Business Use Case 🏢
eBay intends to boost its stock performance by analyzing online discussions to shape better business strategies. The overall goal is to enhance proactive decision-making concerning eBay stock volatility

## Data Sources 📡
- **Reddit**: Data is scraped from the subreddit *WallStreetBets*, focusing on discussions about eBay.
- **Business Insider**: Articles related to eBay and stock data are scraped from this site.

## Web Scraping Routines 🕸️
### Reddit Scraping
1. **Browser Automation**: Utilize Selenium WebDriver for browser automation.
2. **Data Collection**: Navigate to the WallStreetBets subreddit and collect data.
3. **HTML Content Saving**: Parse and save the HTML content of each post.
4. **Database Insertion**: Insert post details into MongoDB.

### Business Insider Scraping
1. **Data Collection**: Automate browsing to collect article links and stock data
2. **Parsing HTML**: Parse the saved HTML files to extract text content.
3. **Database Insertion**: Insert article details into MongoDB.

## Technologies Used 💻
- **Selenium**: For browser automation.
- **BeautifulSoup**: For parsing HTML content.
- **MongoDB**: For storing scraped data efficiently.

