# Scraping TripAdvisor with Selenium 2020 *

Python implementation of web scraping of TripAdvisor with Selenium in a new 2020 website.

The python function is fully commented, write me if you have doubts.

Features implemented: 
  - The click function to open the "more" button of the reviews 
  - The click function to change the page
  - The click function to select only the desired rating (ex: if you wanna only the reviews with 5 stars)
  
In the .csv file "reviewALL.csv" there is an exemple of dataset approximately with 10000 italian reviews labeled from 1 to 5 stars.

*This activity has been supported by a grant from the Project IDEHA - PON "Ricerca e Innovazione" 2014-2020 - Innovation for Data Elaboration in Heritage Areas, Azione II

# Update by Hammamnash #

  1. Fixed the code to meet latest patch on tripadvisor (they changed some tags)
  2. Fixed error while scrapping Hotel Items (Hotels and Attraction has different tags)
  3. Now you can scrap as much as Hotels OR Attractions URLs in slingle run
  4. Fixed emoji error wirh ascii encoding

Still Thanks to the original authos, giuseppegambino
