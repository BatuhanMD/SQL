Q1 -> film tablosunda bulunan filmleri rating değerlerine göre gruplayınız.

S1 -> SELECT rating,COUNT(title) FROM film GROUP BY rating;

Q2 -> film tablosunda bulunan filmleri replacement_cost sütununa göre grupladığımızda film sayısı 50 den fazla olan replacement_cost değerini ve karşılık gelen film sayısını sıralayınız.

S2 -> SELECT replacement_cost,COUNT(title) FROM film GROUP BY replacement_cost HAVING COUNT(title) > 50;

Q3 -> customer tablosunda bulunan store_id değerlerine karşılık gelen müşteri sayılarını nelerdir?

S3 -> SELECT store_id,COUNT(customer) FROM customer GROUP BY store_id;

Q4 -> city tablosunda bulunan şehir verilerini country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısı barındıran country_id bilgisini ve şehir sayısını paylaşınız.

S4 -> SELECT country_id,COUNT(city) FROM city GROUP BY country_id ORDER BY Count(city) DESC LIMIT 1;
