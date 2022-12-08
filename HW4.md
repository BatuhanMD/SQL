S1 -> SELECT DISTINCT replacement_cost FROM film 

S2 -> SELECT COUNT(DISTINCT replacement_cost) FROM film 

S3 -> SELECT COUNT(*) FROM film WHERE title LIKE 'T%' AND rating = 'G'

S4 -> SELECT COUNT(*) FROM country WHERE country LIKE '_____'

S5 -> SELECT COUNT(*) FROM city WHERE city ILIKE '%R'