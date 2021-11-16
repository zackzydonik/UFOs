# UFOs

## Project Overview
The purpose of this analysis is to create an HTML page presenting data on UFOs from a javascript data file.

## Resources
- Data Source: data.js
- Software: Visual Studio Code, 1.60.1

## Results
To filter through the data on the webpage a user must load the page and enter the search parameters in the fields to the left. As new search criteria are entered, the table will automatically filter to the selection.

For example, a user will first come to the landing page that will display all the data in the table. 

![image_name](https://github.com/zackzydonik/UFOs/blob/1f5cb7ff627e2570316db23aed14b03c7f5d74f3/static/images/Homepage.png)

They can then filter by date for example 1/13/2020 and ackerman to recieve the one row of data that matches this search criteria.

![image_name](https://github.com/zackzydonik/UFOs/blob/1f5cb7ff627e2570316db23aed14b03c7f5d74f3/static/images/Filtered.png)

## Summary
One drawback of the new design is that the search criteria will only match rows that have both criteria, not one or the other.

Two recommendations for further development include:
1. A filter allowing users to toggle the option of selecting data with either search criteria may be convenient for users.
2. The page could also incororate web scraping to act as a living link to fresh data, rather than to static old data.