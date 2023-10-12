# OLG Web Scraping Looker Studio Project

This project consists of web scraping data from an OLG website using Python (BeautifulSoup, Pandas), and converting it into a csv file to be used for data visualization. 

The data collected was the winning tickets of +$10,000 CAD from OLG in Ontario between the dates, March 1st 2023 - September 1st 2023. 

Additonally, Looker Studio (formerly know as Data Studio) was the BI tool used to visualize this data.

## Visualizations

The Looker Studio Data Visualization file is here if you wish to explore:

https://lookerstudio.google.com/reporting/a49b12dd-3659-4137-8955-3212b67df288

#### Preview
The following images show the types of visualizations that were performed using Looker Studio:

<img width="797" alt="image" src="https://github.com/Saranjen/OLG_WebScrape/assets/103857336/5ae59397-383c-45b7-acc5-a60d88beedcd">

<img width="776" alt="image" src="https://github.com/Saranjen/OLG_WebScrape/assets/103857336/f0efdcc9-5132-474a-9564-d86bc07adff9">

<img width="759" alt="image" src="https://github.com/Saranjen/OLG_WebScrape/assets/103857336/6f958242-ddfa-4f93-a79c-2a669eea4c75">


## Findings

1.) Found the number of winning Ontario OLG Tickets, the number of different winning stores, and number of different winng OLG products

2.) Discovered correlations in the time trends between Average Amount Won per Month-Year and Number of Winning Tickets per Month-Year within the time range. What was found
    is that there's an inverse relationship between the two trends, as when the average value amount for a month is high, the number of winning tickets decrease, and vice versa.

3.) With geomapping, it was found that more winning tickets occurred in Toronto, which makes sense seeing how Toronto is the most populated city in Canada.

4.) With the distribution plots created, it's become clear, what winning ticket amounts come up the most ($10k), what OLG store sells the most winning tickets (Petro Canada), and 
  what kind of OLG ticket wins the most (Daily Keno, Lotto 649).

5.) There is also now additional insight with what regions of Ontario sells the most winning tickets, which shows that Scarborough came first, 
with the North York region being a close second.

6.) Information on the average value of winning tickets per store compared to the number of winning tickets per store was found. This information is really important as it displays
the consistency in which certain stores are selling tickets of a specific value.


## Resources

The website that was webscraped to acquire the OLG data was:

https://about.olg.ca/winners-and-players/ticket-information/where-winning-tickets-were-sold/


