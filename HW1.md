Q1 -> film tablosunda bulunan title ve description sütunlarındaki verileri sıralayınız.

S1 -> SELECT title,description FROM film

Q2 -> film tablosunda bulunan tüm sütunlardaki verileri film uzunluğu (length) 60 dan büyük VE 75 ten küçük olma koşullarıyla sıralayınız.

S2 -> SELECT * FROM film WHERE length > 60 AND length <75

Q3 -> film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99 VE replacement_cost 12.99 VEYA 28.99 olma koşullarıyla sıralayınız.

S3 -> SELECT * From film WHERE rental_rate = 0.99 AND replacement_cost = 12.99 OR replacement_cost = 14.99 

Q4 -> customer tablosunda bulunan first_name sütunundaki değeri 'Mary' olan müşterinin last_name sütunundaki değeri nedir?

S4 -> last_name = 'Smith'

Q5 -> film tablosundaki uzunluğu(length) 50 ten büyük OLMAYIP aynı zamanda rental_rate değeri 2.99 veya 4.99 OLMAYAN verileri sıralayınız.

S5 -> SELECT * From film WHERE NOT length > 50 AND NOT (rental_rate = 2.99 OR  rental_rate = 4.99)
