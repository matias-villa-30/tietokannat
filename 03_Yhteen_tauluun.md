# Yhteen tauluun kohdistuvien kyselyiden harjoitukset

### Tehtävä 1

SELECT * FROM goal;

![ruudunkaappaus](https://i.imgur.com/tFme2Yk.png)

### Tehtävä 2

SELECT name airport_type FROM airport WHERE iso_country = "FI";

![screenshot](https://i.imgur.com/DStKQ15.png)

### Tehtävä 3

SELECT name FROM airport WHERE iso_country="FI" ORDER BY name ASC;

![screenshotti](https://i.imgur.com/awbmBGP.png)

### Tehtävä 4

SELECT name, type FROM airport WHERE iso_country = "FI" ORDER BY type, name;

![screenshot](https://i.imgur.com/iqXolWc.png)

### Tehtävä 5

SELECT name FROM country WHERE name LIKE "F%";

![screenshot](https://i.imgur.com/wTXsDFX.png)

### Tehtävä 6

SELECT name FROM country WHERE name LIKE "%f%";

![screenshot](https://i.imgur.com/XzuLXOs.png)

### Tehtävä 7

SELECT location from game WHERE location LIKE "%c";

![screenshot](https://i.imgur.com/iZmHxll.png)

### Tehtävä 8

SELECT co2_consumed FROM game WHERE screen_name="Ilkka";

![screenshot](https://i.imgur.com/XywUzKw.png)

### Tehtävä 9

SELECT co2_budget FROM game LIMIT 1;

![screenshot](https://i.imgur.com/ugHULF5.png)
