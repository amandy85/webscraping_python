# Web Scraping Coding Quotes

This Python script scrapes coding-related quotes from the GeeksforGeeks website and prints them to the console.

## Description

The script uses:
- `BeautifulSoup` for parsing and navigating HTML content
- `requests` for fetching web pages
- `urllib` for URL handling (though not actively used in current version)

It specifically targets quotes from the page "Coding Quotes for Software Engineers" on GeeksforGeeks.

## How to Use

1. Ensure you have Python installed
2. Install required packages:
   ```
   pip install beautifulsoup4 requests pandas
   ```
3. Run the script:
   ```
   python script_name.py
   ```

## Output

The script will print all coding quotes found in the blockquotes section of the webpage.

## Future Improvements

- Save quotes to a file (CSV/JSON)
- Add error handling for network requests
- Implement quote filtering or randomization
- Create a quote-of-the-day feature

## Dependencies

- Python 3.x
- beautifulsoup4
- requests
- pandas (though not currently used in processing)

## License

This project is open source and available under the MIT License.
