# HOR_T_SCRAPPER

# Web Scraper

This application is a web scraper implemented in Python using PyQt5. It provides a graphical user interface (GUI) for users to scrape data from a web page by entering a URL and selecting either links or images to scrape.

## Features

- Scrape Links: Extract the links from the web page.
- Scrape Images: Extract the images from the web page.

## Usage

1. Enter the URL of the web page in the provided "URL" text field.
2. Select the desired data to scrape by checking the corresponding radio button:
   - If "Links" is selected, the application will extract the links from the web page.
   - If "Images" is selected, the application will extract the images from the web page.
3. Click the "Scrape" button to initiate the scraping process.
4. The scraped data will be displayed in the text area below.
5. To save the scraped data as a CSV file, click the "Save" button and choose a location to save the file.

**Note:** Make sure you have a stable internet connection to successfully scrape web pages.

## Requirements

- Python 3.x
- PyQt5
- requests
- BeautifulSoup

## Author

Mohammed Zayed

## License

This project is licensed under the MIT License.

## Acknowledgements

- PyQt5: Python bindings for Qt framework
- requests: HTTP library
- BeautifulSoup: HTML parsing library
