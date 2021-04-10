# Robinhood-Clone
semi functional clone of robinhood (no API, no database)

requires apache (or for the brave nginx)

drop in /var/www/html

see directory us/en/stocks

* navigating to "http://127.0.0.1/us/en/stocks/A.html" (login semi functions but no database to check login and password reset)
 
![s1](https://raw.githubusercontent.com/c4pt000/Robinhood-Clone/main/semi-functioning-login.png)

* navigating to "http://127.0.0.1/us/en/stocks/A.html" the last know price loads without API access
 
![s1](https://raw.githubusercontent.com/c4pt000/Robinhood-Clone/main/last-known-stock-price-no-api.png)

* followed by 404 for "http://127.0.0.1/us/en/stocks/A.html"
 
![s1](https://raw.githubusercontent.com/c4pt000/Robinhood-Clone/main/stock-price-no-api-404.png)

