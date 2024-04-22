# Splinter_BeautifulSoup_HTML_challenge
 
The purpose of this mini project was to utilize webscraping to obtain data about from articles about Mars as well as scarpe table data about Mars. To do this I used beautifulsoup, splinter, pandas, numpy and then matplotlib in orded to create visualizations.


## part 1 scaraping Mars articles

To begin this part of the challenge I first imported splinter and beautifulsoup. Splinter was used to open a website and beautiful soup was used to parse and scrape the data from the website. Using beautifulsoup I scraped the titles and the preview text of multiple articles about Mars and then stored them as a list of dictionaries. 

## part 2 scarping Mars weather table 

To start part 2 I again imported the python libraries I needed to complete this portion. Those libraries were splinter, beautifulsoup, matplotlib, pandas and numpy. Splinter and beautifulsoup were used to launch a browser then scrape the data from the table. I had to scrape both the headers and the data from the table into two separate lists. Once this was done, the scraped data was then converted into a pandas dataframe. Once the data was converted into the dataframe some of the columns needed to be converted to the correct data type so that mathematical operations could be applied to them. After this was completed I found the average minimum temperature by each month and then turned that into a bar plot (Fig. 1). Then looked at the average atmospheric pressure of each month and turned that into a bar plot as well (Fig. 2). After this a line plot (Fig. 3) of day (x) and minimum temperature (y) was created to help determine how many days on Earth are equivalent to one year on Mars (the time it takes Mars to orbit the sun one time). Based on these 3 figures it was determined that month 3 is the coldest month while month 8 is the warmest on Mars, month 6 is the lowest average pressure and month 9 is the highest average pressure. When estimating the length of a year on Mars in earth days I obtained the answer of 675 and then confirmed the correct answer of 687 using the internet. 
