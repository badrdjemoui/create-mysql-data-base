# create-mysql-data-base

mysql>show databases;

CREATE DATABASE javaee DEFAULT CHARACTER SET utf8 COLLATE utf8_general_ci;

use javaee;

CREATE TABLE  noms (

 id INT( 11 ) NOT NULL AUTO_INCREMENT ,
 
 nom VARCHAR( 200 ) NOT NULL ,
 
 prenom VARCHAR( 200 ) NOT NULL ,
 
 PRIMARY KEY ( id )
 
) ENGINE = INNODB;


show table;

INSERT INTO noms(nom, prenom) VALUES("djemoui", "badr");

select * from noms;
