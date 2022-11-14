# SQL-ODEV-4-
www.patika.dev
film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.
1) SELECT DISTINCTVreplacement_cost FROM film;

film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?
2) SELECT COUNT(DISTINCT replacement_cost) FROM film;

film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?
3)SELECT COUNT(title) FROM film
 WHERE title LIKE 'T%' and rating='G';

country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?
4)SELECT COUNT(*) FROM country
  WHERE country LIKE '_____';
 
 city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?
5)SELECT COUNT(*) FROM city
  WHERE city ILIKE '&r';

 
