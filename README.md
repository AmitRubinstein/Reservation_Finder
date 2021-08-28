# reservation_finder

This program was designed to help find appealing restaurant reservations more easily. This program queries for reservations on OpenTable 
based on user-provided input and cross-references the results with Yelp. The program then returns available reservations for restaurants with 4+ stars on Yelp.

OpenTable reservations and Yelp ratings are scrapped from the internet using a combination of Selenium and BeautifulSoup.

The program utilizes a GUI to solicit the user's input and to return the search results.

GUI to get reservation detials from the user:
![alt text](https://github.com/AmitRubinstein/ReservationFinder/blob/main/GUI%20Screenshots/GetReservationDetails.png?raw=true)

GUI to return search results:
![alt text](https://github.com/AmitRubinstein/ReservationFinder/blob/main/GUI%20Screenshots/SearchResults.png?raw=true)

Clicking on one of the available reservation times will direct the user to the restaurant's OpenTable page.
![alt text](https://github.com/AmitRubinstein/ReservationFinder/blob/main/GUI%20Screenshots/OpenTable%20Webpage.png?raw=true)
