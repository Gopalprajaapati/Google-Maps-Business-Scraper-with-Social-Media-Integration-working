# Google Maps Business Scraper with Social Media Integration

This project is a web scraper built using **Flask** and **Selenium** to extract business information from Google Maps and integrate social media profiles. It scrapes information like business name, address, contact details, ratings, reviews, and social media links (Facebook, Instagram, LinkedIn, and Twitter).

## Features

- **Google Maps Scraping**: Collect business data from Google Maps based on search queries (e.g., "restaurants near me").
- **Social Media Search**: Automatically fetch social media links (Facebook, Instagram, LinkedIn, Twitter) for the business.
- **Flask Web Application**: A simple web interface to input search keywords and display results.
- **Database Storage**: Results are saved to an SQLite database for persistence and later retrieval.
- **Responsive UI**: Results are displayed in a clean format with pagination.

## Requirements

- Python 3.x
- Flask
- Flask-SQLAlchemy
- Selenium
- WebDriver Manager
- Google Search Python package

## Installation

### 1. Clone the repository:

```bash
git clone https://github.com/Gopalprajaapati/Google-Maps-Business-Scraper-with-Social-Media-Integration.git
cd Google-Maps-Business-Scraper-with-Social-Media-Integration
