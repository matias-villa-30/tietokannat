# Sisäkysely harjoitukset

### Tehtävä 1

SELECT DISTINCT country.name

FROM country

RIGHT JOIN airport

ON country.iso_country = airport.iso_country

WHERE airport.name LIKE "%Satsuma%";

![screenshot](https://i.imgur.com/MOEyFRV.png)

### Tehtävä 2

SELECT airport.name
FROM airport
JOIN country ON airport.iso_country = country.iso_country
WHERE country.name LIKE "%Monaco%";

![screenshot](https://i.imgur.com/bk4eWO5.png)

### Tehtävä 3

SELECT screen_name FROM game WHERE id IN(SELECT game_id FROM goal_reached WHERE goal_id IN(SELECT id FROM goal WHERE goal.name LIKE "%clouds%"));

![screenshot](https://i.imgur.com/Lmu7tnh.png)

### Tehtävä 4

SELECT name FROM country WHERE iso_country NOT IN (SELECT iso_country FROM airport);

![screenshot](https://i.imgur.com/3a2d1JY.png)

### Tehtävä 5

SELECT goal.name FROM goal WHERE id NOT IN(SELECT goal_id FROM goal_reached WHERE game_id NOT IN (SELECT id FROM game WHERE screen_name LIKE "%Heini%"));

![screenshot](https://i.imgur.com/mcdyGo4.png)
