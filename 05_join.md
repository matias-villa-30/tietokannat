# Join harjoitukset

### Tehtävä 1

SELECT country.name as "country name", airport.name as "airport name"

FROM country JOIN airport on airport.iso_country = country.iso_country

WHERE country.name = "Finland" AND scheduled_service = "yes";

![screenshot](https://i.imgur.com/AwfQi1r.png)


### Tehtävä 2

SELECT game.screen_name, airport.name

FROM airport

JOIN game ON airport.ident = airport.ident

WHERE airport.ident = game.location;

![screenshot](https://i.imgur.com/mvR0iwi.png)


### Tehtävä 3

SELECT game.screen_name, country.name
FROM game
JOIN airport ON game.location = airport.ident
JOIN country ON airport.iso_country = country.iso_country;


![screenshot](https://i.imgur.com/Hr4tn9J.png)


### Tehtävä 4

SELECT name, screen_name FROM airport

LEFT JOIN game on ident = location

WHERE name LIKE "%Hels%";

![screenshot](https://i.imgur.com/2jzwZIU.png)


### Tehtävä 5



![screenshot]()
