# Web Crawler Search Engine

## Overview
This project is a web crawler and search engine that crawls a website, indexes its content, and provides a user-friendly search interface. The system uses the Whoosh library for indexing and Flask for the web interface.

## Features
- Crawls and parses all HTML pages from a starting URL.
- Builds an index with Whoosh for fast and efficient search.
- Supports search queries with filters (date range, domain).
- Pagination for large result sets.
- Dark mode and a modern, responsive user interface.


## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/johndoe/web-crawler.git

## Requirements
- Python 3.x
- Flask
- Whoosh
- Requests
- BeautifulSoup4

## Code Structure
- `crawler.py`: Contains the logic for crawling and indexing.
- `app.py`: Implements the Flask application, indexing, and search functionality.
- `index.html`: Frontend template for the home page (search form).
- `results.html`: Frontend template for displaying search results.
- `search.html`: Template for handling search inputs and displaying output.
