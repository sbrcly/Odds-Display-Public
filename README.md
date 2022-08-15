# Odds-Display-Public
Public repository for Odds Display

### This application pulls in sports betting odds from an assortment of different sportsbooks.

### Server Side:
#### Another tool I built (https://github.com/sbrcly/Odds-Tracker-Public) pulls in the data using API's. It then parses and stores that data into a Google BigQuery table.
#### This tool then pulls that data from the BigQuery table using SQL and sends the data to the client utilizing Socket.io.

### Client Side:
#### The client receives, processes and stores the data into a live updating table.
#### Sports traders use this data to determine where the market is for a particular bet.
#### This tool gives them a live view of where our betting odds are compared to some of the other big books in the market.
#### Traders can choose between the MoneyLine, Spread and total. They can also filter the table using the filters in the navbar, or by clicking on the stars to add games to their favorites, then clicking the "Favorites" tab.

### Here is a breif video of how it works:


