# Web Scraper – Short-Term Apartment Rentals

This project is a web scraper built with ```Selenium``` and ```undetected-chromedriver``` to extract short-term apartment rental data from OLX.ba. It navigates through multiple pages, collects ad details, and saves the data into a CSV file for further analysis.

## Features

- Resumes from the last scraped page to avoid redundant scraping.
- Avoids duplicate listings by checking already saved links.
- Extracts key rental information, including title, price, description, and additional details.
- Implements scrolling and retry mechanisms to improve data collection.
- Saves data in CSV format.

## Installation

1. Clone the repository:
  ```
  git clone https://github.com/machinely79/web-scraper-short-term-apartment-rentals.git
  cd web-scraper-short-term-apartment-rentals
  ```

2. Create a virtual environment (optional): 

```
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```

3. Install dependencies:

```
pip install -r requirements.txt
```

## Notes

- Ensure you have Google Chrome installed.
- If undetected-chromedriver stops working, try updating Chrome or using webdriver-manager.

## License

This project is licensed under the MIT License.
