# Arabic News Websites Scrapers - For Arabic Fake News Detection Dataset

This project aims to construct a robust dataset for detecting fake news in Arabic. In addition to distinguishing articles as fake or real, students will categorize them by topic. The dataset will be compiled from reputable fact-checking websites, ensuring an equitable mix of fake and authentic stories across diverse subjects such as politics, religion, health, and more.

## Table of Contents

- [Introduction](#introduction)
- [Objective](#objective)
- [Task](#task)
- [Guidelines](#guidelines)
- [Websites Scrapped From](#websites-scrapped-from)
- [Installation](#installation)
- [Usage](#usage)
- [Data Saved in CSV Files](#data-saved-in-csv-files)

## Introduction

Fake news has become a significant issue in today's digital age, with misinformation spreading rapidly across various platforms. This project aims to address this issue by creating a dataset specifically for detecting fake news in Arabic. By categorizing articles by topic, we can gain insights into the dissemination of fake news across diverse subjects.

## Objective

The primary objective of this project is to construct a comprehensive dataset for detecting fake news in Arabic. The dataset will include articles from reputable fact-checking websites and will be categorized by topic to provide a nuanced perspective on the spread of misinformation.

## Task

- **Data Collection**: Scraping articles from trustworthy Arabic fact-checking websites, ensuring variety in topics and sources.
  
- **Annotation**: Each article will be classified as fake or real and sorted by topic.

## Guidelines

1. **Data Collection**: Articles will be scraped from reputable Arabic fact-checking websites. Special attention will be given to ensuring a diverse range of topics and sources to create a balanced dataset.

2. **Annotation**: Each scraped article will be manually classified as either fake or real. Additionally, articles will be categorized by topic, covering domains such as politics, religion, health, and more.

## Websites Scrapped From

The dataset will be compiled by scraping articles from the following reputable Arabic fact-checking websites:

- **Aljazeera**
- **BBC News**
- **CNN Arabia**
- **Fatabyyano**
- **Misbar**
- **Verify-Sy**
- **Matsd24**

These websites are known for their credibility and provide a diverse range of news articles across various topics.

## Installation

To use the web scrapers in this project, follow these steps:

1. Click on the "Fork" button in the upper-right corner of [this repository](https://github.com/Nahla-yasmine/Arabic-News-Scraper). This will create a copy of the repository under your GitHub account, or you can use the `gh repo fork Nahla-yasmine/Arabic-News-Scraper`.
2. Clone it to your local machine using `git clone https://github.com/your-username/Arabic-News-Scraper.git`.
3. Navigate to the folder of the desired web scraper.
4. Run the Python script corresponding to the web scraper you want to use.

## Usage

Each web scraper in this project is designed to extract news articles from a specific Arabic news website. To use a web scraper, follow these steps:

1. Navigate to the folder of the desired web scraper.
2. Open the Python script corresponding to the web scraper.
3. Run the script using Python.
4. The script will scrape the specified website and save the extracted data to a CSV file.

## Data Saved in CSV Files

The data extracted by each web scraper is saved in CSV (Comma-Separated Values) files. 
These files were merged using the `DATA_MERGING_TOOL.IPYNB` allowing the addition of the missing information and handling the differences in the data structures .
Each row in the CSV file represents a single news article and contains the following information:

- **Title**: The title of the news article.
- **Label**: The label or category of the news article (fake or real).
- **Category Name**: The category or section of the news website where the article is published.
- **Article Content**: The full text content of the news article.
- **Article Date**: The date when the news article was published.
- **Article Correction**: The correction of the fake news statement if availble .

The CSV file provide structured data that can be easily imported into data analysis tools or databases for further processing and analysis.
can be found under the name of `ARABIC-NEWS-CLASSIFICATION-MERGED.zip` (The file is Zipped due to big upload size).

