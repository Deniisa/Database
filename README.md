# Database

In this repository I added samples of my work that I have done during my practical **Database** course.

I created a Database for an online store, using **DbDesigner.net** to design the tables, which can be observed below. 

![DbDesigner work sample](https://github.com/Deniisa/Database/blob/main/DB%20Course%20_%20DbDesigner.net.png)


To create the Database, I used **phpMyAdmin** and I worked with **SQL** for **CRUD** operations. 


![Database in phpMyAdmin](https://github.com/Deniisa/Database/blob/main/localhost%20_%20127.0.0.1%20_%20db%20course%20_%20phpMyAdmin%205.1.1.png)

![Sample of table in phpMyAdmin](https://github.com/Deniisa/Database/blob/main/localhost%20_%20127.0.0.1%20_%20db%20course%20_%20address%20_%20phpMyAdmin%205.1.1.png)


Examples of CRUD operations from  my course: 

1. DELETE FROM address WHERE AddressID = 3 

2. INSERT INTO product VALUES (NULL, 'Televizor LG', 999) 

3. SELECT * FROM product WHERE ProductPrice < 500 AND ProductPrice > 100
   SELECT * FROM customer WHERE CustomerName LIKE 'P%' 
   
4. UPDATE product SET ProductPrice = 26 WHERE ProductID = 3

5. SELECT c.CustomerName, c.CustomerSurname, a.AddressDetails, a.AddressCity 
   FROM customer AS c 
   RIGHT JOIN address AS a 
   ON c.CustomerID = a.CustomerID 
