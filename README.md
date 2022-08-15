# hiretutor
Crud operation using Nodejs and Mysql

First clone the repository.Then create table on workbench using following:

CREATE TABLE `expertinfo` (
  `id` int NOT NULL AUTO_INCREMENT,
  `firstName` varchar(45) NOT NULL,
  `lastName` varchar(45) NOT NULL,
  `description` varchar(45) NOT NULL,
  `languages` varchar(45) CHARACTER SET utf8mb4 COLLATE utf8mb4_bin NOT NULL,
  `cost` varchar(45) NOT NULL,
  `image` varchar(45) DEFAULT NULL,
  PRIMARY KEY (`id`)
) ENGINE=InnoDB AUTO_INCREMENT=7 DEFAULT CHARSET=utf8mb4 COLLATE=utf8mb4_0900_ai_ci

Once you have cloned run following commands in terminal:

npm install or npm i, 
nodemon script.js
