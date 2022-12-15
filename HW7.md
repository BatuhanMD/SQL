S1 --> SELECT rating,COUNT(title) FROM film GROUP BY rating;

S2 --> SELECT replacement_cost,COUNT(title) FROM film GROUP BY replacement_cost HAVING COUNT(title) > 50;

S3 --> SELECT store_id,COUNT(customer) FROM customer GROUP BY store_id;

S4 --> SELECT country_id,COUNT(city) FROM city GROUP BY country_id ORDER BY Count(city) DESC LIMIT 1;