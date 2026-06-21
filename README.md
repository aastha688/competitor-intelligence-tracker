# EdTech Competitor Intelligence Tracker

## Business Problem
Consulting analysts spend hours manually tracking competitor 
moves. This tool automates it.

## What It Does
Scrapes 5 Indian EdTech competitors weekly, extracts hiring 
and content signals, stores history in SQLite, and generates 
an automated digest report.

## Key Finding (Week of June 2026)
upGrad shows highest hiring activity (score: 32), signalling 
aggressive expansion. Vedantu leads content depth (score: 996).

## Tech Stack
Python | BeautifulSoup | SQLite | Pandas | Requests

## Files
| File | Description |
|------|-------------|
| `competitor_intelligence_tracker.ipynb` | Main scraper notebook |
| `competitor_tracker.db` | SQLite database with weekly history |
| `weekly_digest.txt` | Latest auto-generated digest |
