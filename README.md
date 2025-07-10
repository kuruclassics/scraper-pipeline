# Mommy Marketplace Scraper

This repository stores the code and instructions for the automated
Playwright scraper that collects kids’ activity listings around
Toronto & the GTA every Monday.

**Getting Started**

1. Clone or download the repo  
2. Create a `.env` file (see below)  
3. Run `python scraper.py`

**Environment variables**

| Variable          | Purpose                         |
|-------------------|---------------------------------|
| XANO_API_KEY      | Auth key to post data to Xano   |
| MAPBOX_TOKEN      | Needed for geocoding addresses  |
| STRIPE_SECRET     | (future) billing hooks          |
