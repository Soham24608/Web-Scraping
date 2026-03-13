# 📚 Books Web Scraping Project

This project demonstrates a web scraping workflow using Python to collect book information from the practice website  
[Books to Scrape](https://books.toscrape.com/).

The project scrapes multiple pages of book listings, extracts important details such as **book title, price, and rating**, and stores the data in a structured dataset for further analysis.
 ## 🚀 Project Overview ##

The objective of this project is to understand and implement the complete web scraping pipeline.

The workflow includes:

Scraping 50 pages of book listings from the website

Saving each webpage locally as an HTML file

Parsing the HTML content using BeautifulSoup

Extracting book details such as:

Book Title

Price

Rating

Organizing the extracted data into a structured dataset using Pandas

Exporting the final dataset to a CSV file

## 🛠️ Technologies Used ##

Python

Jupyter Notebook

BeautifulSoup

Pandas

Requests library

HTML Parsing

## ⚙️ Environment Setup ##

The project environment was configured using
Anaconda and executed in
Jupyter Notebook.

To install the required HTML parsing libraries, the following command was executed in Anaconda Prompt:

 ## conda install beautifulsoup4 lxml ##

This installs:

BeautifulSoup for parsing HTML documents

lxml for faster HTML/XML processing

## 📂 Project Files ##

You can directly access the project files using the links below:

📓 Web Scraping Notebook
(Downloads 50 webpages and saves them locally)
https://github.com/Soham24608/Web-Scraping/blob/ac97f4f137cde2eb3f163736d0d71d291ad6a513/Web_Scraping.ipynb

📓 BeautifulSoup Data Extraction Notebook
(Parses HTML and extracts book information)
https://github.com/Soham24608/Web-Scraping/blob/ac97f4f137cde2eb3f163736d0d71d291ad6a513/Beautifulsoup.ipynb

📊 Scraped Dataset (CSV)
(Contains extracted book title, price, and rating)
https://github.com/Soham24608/Web-Scraping/blob/ac97f4f137cde2eb3f163736d0d71d291ad6a513/data.csv

## 📁 HTML Pages Folder ##
(Contains the saved HTML pages scraped from the website)
https://github.com/Soham24608/Web-Scraping/tree/ac97f4f137cde2eb3f163736d0d71d291ad6a513/htmls

## 📊 Dataset Information ##

The final dataset contains the following fields:

Column	Description
Book Title	Name of the book
Price	Price of the book
Rating	Customer rating

This dataset can be used for data analysis, visualization, or further data science projects.

## 🎯 Learning Outcomes ##

Through this project I practiced:

Web scraping using Python

Downloading and storing webpages locally

HTML parsing using BeautifulSoup

Extracting structured data from webpages

Organizing data using Pandas DataFrames

Exporting datasets into CSV format
