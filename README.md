# Web Crawler + Mini Search Engine

A domain-specific search engine built in Python that crawls webpages, processes their text, builds an inverted index, and ranks search results using TF-IDF.

## Features

- BFS-based web crawling with configurable crawl depth and page limits
- URL normalization and deduplication
- HTML parsing and text extraction using BeautifulSoup
- Text preprocessing with tokenization, lowercasing, punctuation and stop-word removal
- Inverted index for efficient document retrieval
- TF-IDF based search ranking
- Interactive search through the notebook
- Asynchronous concurrent HTTP fetching
- Performance benchmarking for sequential vs concurrent fetching
- Search latency measurement including average and P95 latency

## Architecture

Seed URL
→ BFS Crawler
→ URL Deduplication
→ HTTPX + BeautifulSoup
→ Text Preprocessing
→ Inverted Index
→ TF-IDF Ranking
→ FastAPI Search API

## Tech Stack

- Python
- HTTPX
- BeautifulSoup
- FastAPI
- Scikit-learn
- Asyncio


## Project Goal

The project focuses on understanding the core engineering behind a small search engine rather than building a production-scale search platform. It demonstrates web crawling, data structures, information retrieval, API development, asynchronous programming, and performance measurement.
