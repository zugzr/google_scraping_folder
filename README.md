# Google Maps Website Scraper Chrome Extension

This Chrome extension allows you to scrape data from Google Maps search results pages and download it as a CSV file.

## Features
- Scrapes data (title, phone number, website URL) from Google Maps search results
- Displays scraped data in a table within the extension popup
- Allows downloading the scraped data as a CSV file with a custom file name

## Installation
1. Clone or download this repository
2. Open Chrome and navigate to `chrome://extensions`
3. Enable "Developer mode" in the top right corner
4. Click "Load unpacked" and select the directory containing the extension files

## Usage
1. Navigate to a Google Maps search results page
2. Click the extension icon in the Chrome toolbar 
3. Click the "Scrape Google Maps" button to extract data from the current page
4. Review the extracted data in the table
5. Enter a custom file name (optional) and click "Download as CSV" to save the data

## Notes
- The extension only works on Google Maps search results pages
- It extracts the title, phone number, and website URL for each listing
- If a custom file name is not provided, the default file name "google-maps-data.csv" will be used

## Disclaimer
This extension is for educational purposes only. Scraping data from websites may be against their terms of service. Use at your own risk.
