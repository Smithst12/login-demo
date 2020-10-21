in parent folder on command line:

npm install

npm start

npm start launches the dev server


Need to have a mysql server with 

  host: "localhost",
  user: "root",
  password: "password",
  database: "Login"
  
  
  
  Run this SQL Query: 
  
  CREATE DATABASE Login;

USE Login;

CREATE TABLE User (
userID int NOT NULL AUTO_INCREMENT,
username varchar(20) NOT NULL,
password varchar(20) NOT NULL,
PRIMARY KEY(userID)
);
