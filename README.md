# CodeAlpha_Web-Scrapping

# Web Scraper for "Books to Scrape"

## 📖 Project Description

This project contains a Python script designed to scrape data from the e-commerce practice website, [books.toscrape.com](http://books.toscrape.com). The primary goal is to systematically extract information for all 1,000 books available in the catalog and save it into a structured CSV file for future analysis.

This script was developed to fulfill **Task 1** of a Data Analytics internship application, which required demonstrating skills in web scraping and data acquisition.

## ✨ Features

- Fetches HTML content from all 50 pages of the book catalog.
- Parses the HTML to extract key details for each book: Title, Price, and Star Rating.
- Handles pagination automatically by finding and following the 'next' page link until the last page is reached.
- Structures the collected data cleanly into a list of dictionaries.
- Saves the final dataset of 1,000 books into a single CSV file (`books_data.csv`).

## 🛠️ Technologies Used

- **Python 3.x**
- **Requests:** For making HTTP requests to the website.
- **BeautifulSoup4:** For parsing HTML and extracting data.
- **Pandas:** For structuring the data into a DataFrame and exporting it to a CSV file.

## ⚙️ Setup and Usage

To run this script on your local machine, follow these steps:

**1. Prerequisites**
   - Make sure you have Python 3 installed.

**2. Clone the Repository (Optional)**
   If this project is on a repository like GitHub, you would clone it:
   ```sh
   git clone [YOUR_REPOSITORY_URL]
   cd [repository-folder-name]

**3. Install Dependencies**
Install the necessary Python libraries by running the following command in your terminal:
