1-)Select country from country 
   
   Where country Like 'A%a' ;
   
   
2-)SELECT * FROM country 
   
   WHERE country ~~ '%_____n';
   
3-)SELECT title FROM film 
   
   WHERE title ILIKE '%t%t%t%t';
   
   
4-)SELECT * FROM film 
   
   WHERE title LIKE 'C%' AND length>90 AND rental_rate= 2.99;
