Q1 -> film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?

S1 -> SELECT AVG(rental_rate) FROM film; (2,98)

Q2 -> film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?

S2 -> SELECT Count(title) FROM film WHERE title LIKE 'C%'; (92 adet)

Q3 -> film tablosunda bulunan filmlerden rental_rate değeri 0.99 a eşit olan en uzun (length) film kaç dakikadır?

S3 -> SELECT MAX(length) FROM film WHERE rental_rate = 0.99; (184 dakika)

Q4 -> film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replacement_cost değeri vardır?
 
S4 -> SELECT COUNT(DISTINCT(replacement_cost)) FROM film WHERE length > 150; ( 21 adet)
