# web-scraping-challenge
This challenge builds a web application that scrapes various websites for data related to the Mission to Mars and displays the information in a single HTML page.

All files are stored in the Missions_to_Mars folder. The Jupyter Notebook uses BeautifulSoup, Pandas, and Requests/Splinter to scrape data from the following websites:
- NASA Mars News Site https://mars.nasa.gov/news/
- JPL Featured Space Image https://www.jpl.nasa.gov/spaceimages/?search=&category=Mars
- Mars Weather Twitter Page https://twitter.com/marswxreport?lang=en
- Mars Facts https://space-facts.com/mars/
- USGS Astrogeology site https://astrogeology.usgs.gov/search/results?q=hemisphere+enhanced&k1=target&v1=Mars

The scrape_mars.py file provides functions for scraping the urls. The app.py file uses MongoDB with Flask templating to create a new HTML page that displays all of the information that was scraped. The index.html file is located in the template folder. 

The screenshot folder contains the screenshots of the final application. 