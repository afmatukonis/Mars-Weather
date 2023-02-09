# Mars-Weather
Module-11

**Purpose**

The purpose of this module is to perform a web-scraping on two different Mars NASA pages, extract the text and table data, turn that into a dataframe and then analyze the data. We used Splinter, HTML parsing, Beautiful Soup, Pandas and JSON to perform the tasks. 

**Overview**

We were asked by Robin to help her perform a web-scrape and data analysis for the mission to Mars project for SpaceForce. We are tasked with collecting news items about mars missions from public websites. First we learned how to drill down into specific websites and find declarations and metatags and CSS using the class selector. 

First we identified the webpage we wanted to scrape and set up jupyter notebook and use Splinter to automate the browswer. Then we scraped the data using Beautiful Soup and HTML tags. we first extracted all the text elements, then used a for loop to iterate through, and then stored the data in a Python list and export as a json file. 



The next part of the project was to use the same setup but extract data from a Mars weather table. Like before we used splinter to automate the browser and Beautiful Soup to scrape the data. Once we extracted all the table data-row we then again created an empty list and iterated through it to crete a list of rows. Then from that we created a DataFrame from that list of rows. To then analyze the data we checked to see how many months on Mars there were, how many martain days of data there were, what the average low temperature by month was and the average pressure. We then plotted those data points to get a few graphs and compared the Number of Earth Days vs. Martian Annual Weather. Finally we saved the data in a csv file. 


**Results**

Based on our data we determined the following:
-There are 12 months on Mars
-There are 1867 Martian Days
-The coldest month is month 8, and the hottest is month 3
-The month with the lowest atmospheric pressure is month 6, and the highest is month 9
-One year on Mars is about 687 earth days. 