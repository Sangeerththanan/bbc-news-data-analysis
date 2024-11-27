# BBC News Data Collection and Analysis

This project involves collecting data from BBC News, cleaning it, and performing basic analysis on the category distribution of news articles. The final data is exported to a CSV file and visualized in the form of a bar chart, showing the distribution of news categories.

## Project Overview

In this project, we:
- Scrape data from the BBC News website using Python.
- Clean the data by removing duplicates, handling missing values, and ensuring proper URL formatting.
- Analyze the distribution of news categories.
- Visualize the category distribution using a bar chart.

The goal is to demonstrate how to handle real-world data collection, cleaning, and analysis, showcasing foundational data science skills.

## Technologies Used

- **Python** - Programming language used for data collection and analysis.
- **BeautifulSoup** - For web scraping the BBC News website.
- **Pandas** - For data manipulation and cleaning.
- **Matplotlib** - For visualizing the category distribution of news articles.
- **Requests** - For fetching the webpage content.

## Getting Started

To run this project, you need Python and Anaconda installed on your machine. You will also need to install the following dependencies:

1. Clone this repository:
    ```bash
    git clone https://github.com/yourusername/bbc-news-data-analysis.git
    cd bbc-news-data-analysis
    ```

2. Create a new conda environment (optional but recommended):
    ```bash
    conda create --name bbc-news-env python=3.x
    conda activate bbc-news-env
    ```

3. Install the required libraries:
    ```bash
    pip install -r requirements.txt
    ```

    Or install them individually:
    ```bash
    pip install requests beautifulsoup4 pandas matplotlib
    ```

4. Launch Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

5. Open any Jupyter Notebook file in the project directory and run the cells to scrape and analyze BBC news data.

Note: You can use any Jupyter Notebook in this project to run the code and explore the data.

This will:
- Fetch data from the BBC News website.
- Clean the data by removing duplicates and handling missing values.
- Export the cleaned data to a CSV file called `bbc_news_data_cleaned.csv`.
- Generate a bar chart showing the distribution of news categories.

## Project Structure

This project analyzes BBC news data. 

Here's a breakdown of the project files:

* **bbc_news_scraper.ipynb:** Python script to fetch, clean, and analyze data from BBC News.
* **bbc_news_data.csv:** Raw scraped data from BBC News (before cleaning).
* **bbc_news_data_cleaned.csv:** Cleaned and processed BBC news data.
* **requirements.txt:** Text file listing all Python libraries required for this project.
* **HTML_structure.txt:** A text file containing the HTML structure of the scraped news articles from BBC News.
* **README.md:** This file (you're reading it now!) provides project documentation.

## Features

- **Data Collection**: Scrapes the BBC News homepage for news headlines, descriptions, categories, article links, and images.
- **Data Cleaning**: Removes duplicates, handles missing values, and ensures URLs are formatted correctly.
- **Data Analysis**: Analyzes the distribution of categories in the dataset.
- **Data Visualization**: Creates a bar chart showing the number of articles per category.

## Example Output

The script will output the cleaned data in `bbc_news_data_cleaned.csv`, and the analysis will generate a bar chart similar to the following:

![Category Distribution Chart](https://github.com/user-attachments/assets/a1a35afb-246b-4e12-b8de-2da6eb629d3b)

