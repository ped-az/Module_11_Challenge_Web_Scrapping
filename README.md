# Module_11_Challenge_Web_Scrapping

Welcome to the Web Scrapping Challenge

# Overview: 
1. Deliverable 1: Scrape titles and preview text from Mars news articles.
2. Deliverable 2: Scrape and analyse Mars weather data, which exists in a table.

Part 1:  Scrape Titles and Preview Text from Mars News
- Used automated Browsing to visit the Mars News Site: "https://static.bc-edx.com/data/web/mars_news/index.html"
- Created a Beautiful Soup object to extract text elements
- Extracted the Titles, Previews and Article Earth Dates (Not Required But Made sense to add)
    - Stored the above ina  dictionary & a Python List
    - Printed the list into a notebook

Part 2: Scrape and Analyse Mars Weather Data
- Used automated Browsing to visit the Mars Daily Temperature: "https://static.bc-edx.com/data/web/mars_facts/temperature.html"
- Created a Beautiful Soup object and use it to scrape the data in the HTML table.
- Assembled the scraped data into a Pandas DataFrame.
- Examined the data types that are currently associated with each column.
- Analyse your dataset by using Pandas functions to answer the following questions:
    - How many months exist on Mars?
        - 12 Months
    - How many Martian (and not Earth) days worth of data exist in the scraped dataset?
        - 1867
    - What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
        - The coldest month was 3.
        - The hottest month was 8.
    - Find the average minimum daily temperature for all of the months.
        - In the analysis
    - Plot the results as a bar chart.
        - In the analysis

    - Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
    - Find the average daily atmospheric pressure of all the months.
    - Plot the results as a bar chart.
        - All three above in analysis.
    - About how many terrestrial (Earth) days exist in a Martian year? To answer this question: Consider how many days elapse on Earth in the time that Mars circles the Sun once. Visually estimate the result by plotting the daily minimum temperature.
        - IN analysis
    - Export the DataFrame to a CSV file.
        - File: Mars_Temp_Data