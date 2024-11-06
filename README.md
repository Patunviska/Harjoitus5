# Harjoitus5
Harjoitustehtävässä 5 luodun projektin tarkasteltavat osiot.

HomeController.cs:
HomeController on ohjain mikä hakee JSON-muotoisen datan tiedostosta, muuttaa sen Product-olioiksi 
ja välittää setit tuonne näkymälle eli viewille.

products.json:
Tässä tiedostossa asuu JSON-muotoinen data mistä HomeControllerissa oleva metodi GetProducts hakee datan ja muuttaa sen Product-olioiksi.

Product.cshtml:
View eli näkymä. Tänne HomeController työntää muutetun datan, jotta se voidaan esittää 
käyttöliittymässä html-muodossa.


