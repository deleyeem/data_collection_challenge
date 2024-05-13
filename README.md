# data_collection_challenge

## Project Overview
This project focuses on web scraping Mars-related data from various sources, including news articles and weather data. The goal is to gather valuable information about Mars for further analysis and exploration.

## Background
Web scraping is the process of extracting data from websites. 

## Tools and Libraries

Splinter: tool to automate web browser actions (automatically scan and repeat interactions on websites)

ChromeDriver: enable automation in the Chrome browser

Beautiful Soup: Python library to pull out and parse specific information from a webpage
    - html5lib: package from Beautiful Soup to parse websites
    - lxml: package from Beautiful Soup to parse websites

Pandas: assemble scraped data

## Process Description
collecting data, organizing and storing data, analyzing data, and then visually communicating insights.

Part 1 - Scraping Mars News: 

I scraped titles and preview text from Mars news articles using automated browsing and Beautiful Soup. This involved visiting the Mars News website, identifying elements to scrape, and storing the extracted data in Python data structures.

Part 2 - Scraping and Analyzing Mars Weather Data: 
I scraped and analyze Mars weather data from the Mars Temperature Data Site. This includes extracting data from an HTML table, assembling it into a Pandas DataFrame, analyzing various aspects like temperature and atmospheric pressure, and visualizing the results.
    Which month, on average, has the lowest temperature? The highest?
    Which month, on average, has the lowest atmospheric pressure? The highest?
    A visual estimate (within 25%) of how many terrestrial days exist in a Martian year?

## Conclusion 
Web scraping is a powerful tool for gathering data from the vast resources available on the internet. By leveraging tools like Splinter and Beautiful Soup, I can extract valuable insights from webpages, enabling further analysis and exploration. This project enhances my skills in data collection, organization, analysis, and visualization, contributing to a better understanding of Mars-related information.
