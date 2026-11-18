# Ilorin News Headline Scraper

A small Python script that fetches an Ilorin.info news article and prints its
`<h2>` headings that do not contain links.

## Requirements

- Python 3
- `requests`
- `beautifulsoup4`

Install the dependencies with:

```bash
python -m pip install requests beautifulsoup4
```

## Run

```bash
python web_scrapping_headline.py
```

The script checks for HTTP errors and prints matching headings to the terminal.
The article URL is currently set in the script.
