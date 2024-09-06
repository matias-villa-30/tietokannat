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
