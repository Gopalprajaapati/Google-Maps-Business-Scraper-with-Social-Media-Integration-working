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



2. Create a virtual environment (optional but recommended):
bash
Copy code
python -m venv .venv
Activate the virtual environment:

Windows:

bash
Copy code
.venv\Scripts\activate
Mac/Linux:

bash
Copy code
source .venv/bin/activate
3. Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
4. Run the Flask application:
bash
Copy code
python app.py
5. Open your browser and go to http://127.0.0.1:5000/ to use the application.
How it works
Flask Application: The web interface allows users to input a search keyword (e.g., "restaurants", "law firms"), which is then passed to the scraper.
Selenium Scraping: The scraper uses Selenium to interact with Google Maps and extract business information.
Social Media Integration: The scraper then searches for the business name on Google to find its social media profiles (Facebook, Instagram, LinkedIn, Twitter).
Database: Results are saved in an SQLite database for further use or viewing.
Database Structure
The database stores the following information for each business:

Title: Name of the business.
Link: Google Maps link for the business.
Website: Website URL (if available).
Stars: Google Maps rating stars.
Reviews: Number of reviews.
Phone: Phone number (if available).
Facebook: Facebook link (if found).
Instagram: Instagram link (if found).
LinkedIn: LinkedIn link (if found).
Twitter: Twitter link (if found).
Contributing
Fork the repository.
Create a new branch (git checkout -b feature-name).
Commit your changes (git commit -am 'Add new feature').
Push to the branch (git push origin feature-name).
Create a new Pull Request.
License
This project is licensed under the MIT License - see the LICENSE file for details.

Acknowledgements
Flask
Selenium
Google Search API
vbnet
Copy code

### Key Sections in the README:

- **Project Overview**: Gives a short description of the project and its functionalities.
- **Requirements**: Lists the libraries needed to run the project.
- **Installation**: Step-by-step guide to install and run the project locally.
- **How It Works**: Explains the flow and logic behind the scraping and data handling.
- **Database Structure**: Defines the structure of the database where the results are stored.
- **Contributing**: Instructions for others to contribute to the project.
- **License**: Information about the project's licensing (MIT License is suggested here).
- **Acknowledgements**: Recognizes the tools and libraries used in the project.

You can adjust the details according to your actual project's specifics.

Let me know if you'd like to add more information to the README or need further adjustments!






