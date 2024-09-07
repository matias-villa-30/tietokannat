# Where-osan liitosehto harjoitukset

### Tehtävä 1

SELECT country.name AS "country name", airport.name AS "airport name" FROM country, airport

WHERE airport.iso_country = country.iso_country 

AND country.name = "Iceland";

![screenshot](https://i.imgur.com/ahaeLkc.png)


### Tehtävä 2

SELECT name AS "airport name" FROM airport

WHERE iso_country = "FR" AND type = "large_airport";

![screenshot](https://i.imgur.com/oPued68.png)

### Tehtävä 3

SELECT country.name AS "country_name", airport.name AS "airport_name" FROM airport, country

WHERE country.iso_country = airport.iso_country

AND country.continent = "AN";

![screenshot](https://i.imgur.com/DZeHtH3.png)


### Tehtävä 4

SELECT elevation_ft FROM airport WHERE ident = "EFHK";

![screenshot](https://i.imgur.com/HXnraOd.png)


### Tehtävä 5

SELECT elevation_ft*0.3048 AS 'elevation_m' FROM airport WHERE ident = "EFHK";

![screenshot](https://i.imgur.com/jv5Su2P.png)


### Tehtävä 6

SELECT name FROM airport, game

WHERE location = ident AND screen_name = "Ilkka";

![screenshot](https://i.imgur.com/9NidA5X.png)


### Tehtävä 7

SELECT country.name

FROM airport, game, country

WHERE location = ident AND airport.iso_country = country.iso_country  

AND screen_name = "Ilkka";

![screenshot](https://i.imgur.com/MYW4qV9.png)


### Tehtävä 8

SELECT name FROM goal, goal_reached

WHERE goal_id = id AND game_id = 1;

![screenshot](https://i.imgur.com/tI6GrtO.png)


### Tehtävä 9

SELECT name FROM airport, game
WHERE location = ident AND screen_name = "Ilkka";

![screenshot]()


### Tehtävä 10

![screenshot]()
