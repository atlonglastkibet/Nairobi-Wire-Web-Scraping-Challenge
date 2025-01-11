
# Nairobi Wire Web Scraping

This project demonstrates how to scrape headlines and summaries from **Nairobi Wire**, a popular Kenyan news website. Using **BeautifulSoup** and **requests**, the script extracts key article data for analysis, displaying headlines and summaries in a structured format.

## Features

- Scrapes headlines and summaries from Nairobi Wire's latest articles.
- Outputs the extracted data in a clean and readable format.
- Saves the scraped data to a text file for further analysis and further processing.

## Usage

The project is contained in a **Python Jupyter Notebook** format (`.ipynb`). To use the notebook, simply clone the repository, set up your environment, and run the notebook to scrape data from Nairobi Wire.

### Steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/atlonglastkibet/Nairobi-Wire-Web-Scraping-Challenge.git
   ```

2. Navigate into the project folder:
   ```bash
   cd Nairobi-Wire-Web-Scraping-Challenge
   ```

3. Install the dependencies by running:
   ```bash
   pip install -r requirements.txt
   ```

4. Since a virtual environment is already included in the repository, you can easily activate it:
   ```bash
   source venv/bin/activate  # For macOS/Linux
   .\venv\Scripts\activate   # For Windows
   ```

5. Launch the Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

6. Open and run the notebook to scrape the latest articles from Nairobi Wire.

## Recommendation for Improvement

Currently, the tool does not scrape all pages on the website. A potential improvement could be to add a feature that allows the scraper to navigate through multiple pages, focusing on areas of interest such as **Sports**, **Politics**, or other categories of news. This would enhance the scraper’s ability to collect data across different sections of the site.

## Disclaimer

This project strictly follows ethical web scraping practices. All content scraped belongs to the rightful owners of Nairobi Wire. This project is for educational and personal use only.

## Enjoy!
