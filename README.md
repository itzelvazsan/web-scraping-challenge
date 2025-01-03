# web-scraping-challenge
By: Itzel Vázquez Sánchez

## Project Description

This Week's Challenge consists of two technical products. 

* Deliverable 1: Scrape titles and preview text from Mars news articles.
* Deliverable 2: Scrape and analyze Mars weather data, which exists in a table.

### Part 1: Scrape Titles and Preview Text from Mars News
1. Open the Jupyter Notebook named _part_1_mars_news.ipynb_. 
2. Use automated browsing to visit the Mars news siteLinks to an external site. Inspect the page to identify which elements to scrape.
3. Create a Beautiful Soup object and use it to extract text elements from the website.
4. Extract the titles and preview text of the news articles that you scraped. Store each title-and-preview pair in a Python dictionary and, give each dictionary two keys: _title_ and _preview_.Store all the dictionaries in a Python list. Print the list in your notebook.

### Part 2: Scrape and Analyze Mars Weather Data
1. Open the Jupyter Notebook named part_2_mars_weather.ipynb.
2. Use automated browsing to visit the Mars Temperature Data SiteLinks to an external site.. Inspect the page to identify which elements to scrape. Note that the URL is https://static.bc-edx.com/data/web/mars_facts/temperature.html.
3. Create a Beautiful Soup object and use it to scrape the data in the HTML table. Note that this can also be achieved by using the Pandas read_html function. However, use Beautiful Soup here to continue sharpening your web scraping skills.
4. Assemble the scraped data into a Pandas DataFrame. The columns should have the same headings as the table on the website.
5. Examine the data types that are currently associated with each column. If necessary, cast (or convert) the data to the appropriate datetime, int, or float data types.
6. Analyze your dataset by using Pandas functions to answer the following questions:
    * How many months exist on Mars?
    * How many Martian (and not Earth) days worth of data exist in the scraped dataset?
    * What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
        * Find the average minimum daily temperature for all of the months.
        * Plot the results as a bar chart.
    * Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
        * Find the average daily atmospheric pressure of all the months.
        * Plot the results as a bar chart.
    * About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
        * Consider how many days elapse on Earth in the time that Mars circles the Sun once.
        * Visually estimate the result by plotting the daily minimum temperature of each observation.
7. Export the DataFrame to a CSV file

This Project is the result of the learning lessons of Module 11: Data Cllection from the Data Analysis and Visualization Boot Camp 2024. The main goal is to use the acquired habilities and knowledge in a real case. 


## Table of contents

On the repository you can find the following content:

| Item  |   File Type   |         File Name              |           Description           |
| ----- | ------------- | ------------------------------ | ------------------------------- |
|   1   |    .ipynb     |  part_1_mars_news              |    First part of the challenge  |
|   2   |    .ipynb     | part_2_mars_weather            |    Second part of the challenge |
|   3   |     .csv      |       weather_data             |Csv with data of second excersice|


## How to Use the Project
 
 * To solve the first part: you can use the jupyter notebook _part_1_mars_news.ipynb_. It should run and give you the same results.
 
 * To solve the second part: you can use the jupyter notebook _part_2_mars_weather.ipynb_. It should run, give you the data analysis and save the data in a csv.

## Credits 

The code of this project origins from: starter code provided by the Team of the Data Analysis and Visualization Bootcamp, the solved exercises worked in the Zoom Lessons, [Stackoverflow](https://stackoverflow.com/), [Python Documentation](https://docs.python.org/3/), [pandas documentation](https://pandas.pydata.org/docs/index.html), [Matplotlib Documentation](https://matplotlib.org/stable/index.html) and Microsoft Copilot.
