# Mapping 12 best sandwich restaurants in Chicago

My friend invited me to Chicago during Spring break.

Since I often have subs for lunch, I wanted to find and locate great sandwich places that I can visit.

I used https://www.thrillist.com/eat/chicago/chicago-best-sandwich-bucket-list-40-sandwiches-to-eat-before-you-die to find list of top sandwich places in Chicago.

* I used beautiful soup to scrape data from site above to extract list of name of restruants and corresponding urls.
* I inteded to scape the menus from all the websites using selenium; however, each website had different styles of menus (some menus were pictures, some needed extra clicks to get to menu, etc).

* I manually scraped the address of each restruatns and combined it to the dataset.
--> I used the address (utilizing 'gmaps') to attain 'lattitude' and 'longitude' information.

* I used 'lat' and 'lng' data in geocoding to mark each restraunts on google maps.

