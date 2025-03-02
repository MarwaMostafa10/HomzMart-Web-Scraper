# HomzMart-Web-Scraper
📌 Project Description:
This Python script scrapes product data from HomzMart’s furniture category (Beds) using Selenium. It automates the extraction of key product details such as name, material, size, color, price, and image link. The scraped data is then stored in both CSV and Excel formats for further analysis.

📌 Technologies Used:
Python – Core programming language
Selenium – For web automation and scraping
WebDriver Manager – To handle ChromeDriver installation
Pandas – For handling and exporting data to Excel
Regular Expressions (re) – For text extraction and formatting
CSV & Excel Processing – Data storage for analysis
📌 How It Works:
Navigates through multiple pages (up to 50) of the HomzMart beds category.
Extracts product details, including:
Product Name
Material
Size (if available)
Color
Price
Product Image URL
Scrolls through each page to load more products dynamically.
Saves extracted data into a CSV file (HomzMart.csv).
Converts the CSV file into an Excel file (HomzMart.xlsx) using Pandas.
