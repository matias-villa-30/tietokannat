# Koostetieto kyselyt harjoitukset

### Tehtävä 1

SELECT max(elevation_ft) FROM airport;

![screenshot](https://i.imgur.com/QGNyNKt.png)

### Tehtävä 2

SELECT continent, count(*) 

FROM country

GROUP BY continent;

![screenshot](https://i.imgur.com/tc3YbkW.png)

### Tehtävä 3

SELECT screen_name, count(*) FROM game, goal_reached WHERE id=game_id

GROUP BY screen_name;

![screenshot](https://i.imgur.com/wuhHawP.png)

### Tehtävä 4

SELECT screen_name FROM game WHERE co2_consumed IN(SELECT MIN(co2_consumed) FROM game);

![screenshot](https://i.imgur.com/fnLygxL.png)

### Tehtävä 5

SELECT country.name, count(*) FROM country

JOIN airport ON airport.iso_country = country.iso_country

GROUP by country.iso_country

ORDER by count(*) desc

LIMIT 50;

![screenshot](https://i.imgur.com/lDINibe.png)

### Tehtävä 6

SELECT country.name

FROM airport, country

WHERE airport.iso_country = country.iso_country

GROUP BY country.iso_country

HAVING COUNT(*) > 1000;

![screenshot](https://i.imgur.com/LOidBvy.png)

### Tehtävä 7

SELECT NAME FROM airport  WHERE elevation_ft IN(SELECT MAX(elevation_ft) FROM airport);

![screenshot](https://i.imgur.com/G0F2YG7.png)

### Tehtävä 8

SELECT country.name

FROM country

JOIN airport ON airport.iso_country = country.iso_country

WHERE airport.elevation_ft = (SELECT MAX(elevation_ft) FROM airport);

![screenshot](https://i.imgur.com/S5a2dTW.png)

### Tehtävä 9

SELECT count(*) FROM goal_reached

WHERE game_id = 2;

![screenshot](https://i.imgur.com/pCzkAqz.png)

### Tehtävä 10

SELECT NAME FROM airport

WHERE latitude_deg IN (SELECT MIN(latitude_deg) FROM airport);

![screenshot](https://i.imgur.com/evNxco5.png)
