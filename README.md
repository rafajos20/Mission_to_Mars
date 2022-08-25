# Mission_to_Mars
## Overview
Automate a browser to scrape multiple sites to extract data and images (Beautifulsoup, Splinter). Once extracted, storing the info in a NoSQL database (MongoDB). Then using Flask, create a web application to display the data and images.

## Process
### * 1. Scraping.py
Beautifulsoup and Splinter; drill down into the HTML tags to extract the most recent news article and summary from Mars News site.
Beautifulsoup and Splinter; drill down into the HTML tags to extract the most recent image from Space Images site.
Pandas; scrape Mars/Earth table and read as DataFrame then convert into HTML from Mars Facts site.
Beautifulsoup and Splinter; drill down into the HTML tags to extract all four full size hemisphere images from Mars Hemisphere site.
Store scraped data in MongoDB database.


### * 2. App.py
create app to connect MongoDB through Flask to set up web page.
### * 3. Index.html
create containers to display news article, images, and table.
create 'Scrape New Data' button to perform our scraping function.
refactor code to ensure data displayed is responsive to multiple device sizes.
Bootstrap; customize web page appearance(background color change, jumbotron image fill, button color change, text color change).
