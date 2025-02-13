# Webscraping-CNB

This is a Python script that scrapes current exchange rates from the Czech National Bank (ČNB) without using an API. The data is saved into a CSV file.

## 📌 Features
- Scrapes daily exchange rates from ČNB
- Saves the data to a CSV file
- Uses `requests` and `BeautifulSoup` for web scraping
- Supports multiple currencies

## 🔧 Requirements
Before running the script, make sure you have the following Python libraries installed:

`pip install requests beautifulsoup4 pandas`

## 🚀 Installation & Usage
Clone this repository:
   git clone https://github.com/mw3b3r/Webscraping-CNB.git
   cd Webscraping-CNB

## 📊  Example Output
| Date       | Country  | Currency | Amount | Code | Rate  |
|------------|---------|----------|--------|------|-------|
| 13.02.2025 | Germany | Euro     | 1      | EUR  | 25.055 |
| 13.02.2025 | USA     | Dollar   | 1      | USD  | 24.111 |
| 13.02.2025 | UK      | Pound    | 1      | GBP  | 30.070 |

## 📝 License
This project is licensed under the MIT License - see the LICENSE file for details.



