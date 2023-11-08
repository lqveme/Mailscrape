
```markdown
# Web Scraper

This is a simple Python web scraper that scans a target URL for email addresses.
It starts with a user-defined URL and crawls through the web to find email addresses on web pages.

## Features

- Web scraping using Python
- Crawl web pages to find email addresses
- Limit the number of pages to crawl to prevent infinite crawling
- Handles common exceptions during web requests

## Usage

1. Install the required dependencies by running the following command:

   ```bash
   pip install -r requirements.txt
   ```

2. Run the `web_scraper.py` script:

   ```bash
   python web_scraper.py
   ```

3. Enter the target URL to start scanning for email addresses.

Please note that the program will scan up to 100 web pages by default, and you can change this limit in the script if needed.

## Requirements

Make sure you have the necessary Python libraries installed. You can install them by running the following command:

```bash
pip install -r requirements.txt
```

The script uses the following libraries:

- [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/): For parsing HTML content
- [requests](https://docs.python-requests.org/en/latest/): For making HTTP requests
- [urllib](https://docs.python.org/3/library/urllib.html): For parsing and constructing URLs
- [collections](https://docs.python.org/3/library/collections.html): For using `deque` to manage URLs
- [re](https://docs.python.org/3/library/re.html): For regular expressions

## Limitations

- This script has a default limit of 100 pages to prevent indefinite crawling. You can modify the script to change this limit.
- The program may not find all email addresses, as it relies on regular expressions to detect them.


