# Where-osan liitosehto harjoitukset

### Tehtävä 1

SELECT country.name AS "country name", airport.name AS "airport name" FROM country, airport

WHERE airport.iso_country = country.iso_country 

AND country.name = "Iceland";

![screenshot](https://i.imgur.com/ahaeLkc.png)
