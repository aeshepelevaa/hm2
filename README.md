# hm2
CREATE DATABASE example;
CREATE DATABASE sample;
USE example;
CREATE TABLE users (id SERIAL PRIMARY KEY, name VARCHAR(255) COMMENT 'Имя пользователя');
exit
3.задание 
mysqldump -u root -p example > sample.sql
mysql -u root -p sample < sample.sql  
mysql -u root -p
SHOW DATABASES;
DESCRIBE sample.users;
