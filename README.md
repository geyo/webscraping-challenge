# Mars Article Webscraping

By Grace Yoo

**Programming Languages & Libaries Used:** Python, Beautiful Soup, Splinter, Jupyter Notebook

## Goals
Use Beautiful Soup to:
1. Scrape titles & preview text from Mars news articles from website. 
2. Scrape Mars weather data. 
3. Generate visualizations. 

## Steps

1. Use automated browsing to visit [Mars news site](https://static.bc-edx.com/data/web/mars_news/index.html) and identify which html elements to scrape. 
2. Create a Beautiful Soup object to extract text elements from the website. Isolate article title and article preview elements.
3. Store each title-and-preview pair in a Python dictionary. 
4. Save data as a json file. 
5. Do the same for Mars weather data. 
6. Store as Pandas DataFrame and conduct analysis. 

## Visualizations

### Website to Scrape From

Here is the website the data was scraped from. 

![mars website.png](https://github.com/geyo/webscraping-challenge/blob/main/mars%20website.png)

### Daily Minimum Temperature on Mars

![monthly_temp_mars](https://github.com/geyo/webscraping-challenge/blob/main/daily%20min%20temp%20mars.png)

### Average Daily Minimum Temperature per Martian Month

![temp_mars](https://github.com/geyo/webscraping-challenge/blob/main/martian.png)

### Average Daily Atmospheric Pressure per Martian month

![daily_pressure_mars](https://github.com/geyo/webscraping-challenge/blob/main/atmospheric%20pressure.png)
