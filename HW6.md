S1 --> SELECT AVG(rental_rate) FROM film; (2,98)

S2 --> SELECT Count(title) FROM film WHERE title LIKE 'C%'; (92 adet)

S3 --> SELECT MAX(length) FROM film WHERE rental_rate = 0.99; (184 dakika)

S4 --> SELECT COUNT(DISTINCT(replacement_cost)) FROM film WHERE length > 150; ( 21 adet)