# Päivityskyselyt harjoitukset

### Tehtävä 1

UPDATE game
SET location = (SELECT ident FROM airport WHERE airport.name LIKE "%Nottingham Airport%")
WHERE game.id = 2;

UPDATE game
SET co2_consumed = co2_consumed + 500
WHERE game.id = 2;

![screenshot](https://i.imgur.com/f1S9diZ.png)

### Tehtävä 2

![screenshot](https://i.imgur.com/9yeGz9N.png)

### Tehtävä 3

DELETE FROM goal_reached;

![screenshot](https://i.imgur.com/ePlKUs6.png)

### Tehtävä 4

DELETE FROM game;

![screenshot](https://i.imgur.com/DxnMA2R.png)


