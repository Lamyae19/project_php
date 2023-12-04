# project_php
il faut créer une base de donneés appeler shp en XAMPP
contient deux tableaux :
USERS:</br>
</br>
CREATE TABLE users (
    name TEXT NOT NULL ,
     username VARCHAR(18) NOT NULL PRIMARY KEY,
     email VARCHAR(21) NOT NULL UNIQUE,
     password TEXT NOT NULL );

 PRODUCTS:</br>
 </br>
 CREATE TABLE products (
     id INT NOT NULL ,
     name TEXT NOT NULL,
     price INT NOT NULL,
     PRIMARY KEY (id)
);
et insérer les element suivant en table products
INSERT INTO `products` (`id`, `name`, `price`) 
VALUES ('1', ' Bag', '12'), 
         ('2', 'T-shirts', '20'), 
       ('3', ' Hoodie', '50');
