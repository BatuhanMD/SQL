S1 -> SELECT country FROM country WHERE country LIKE 'A%a'

S2 -> SELECT country FROM country WHERE country LIKE '_____%n'

S3 -> SELECT title FROM film WHERE title ILIKE '%t%t%t%t'

S4 -> SELECT * FROM film WHERE title LIKE 'C%' AND length > 90 AND rental_rate = 2.99