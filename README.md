**We need to create a database using sql to store the student information**

CREATE DATABASE STUDENT_MANAGEMENTS;
USE STUDENT_MANAGEMENTS;
CREATE TABLE STUDENT_REGISTER(
f_name VARCHAR(50) NOT NULL,
	l_name VARCHAR(50) NOT NULL,
	course VARCHAR(30) NOT NULL,
	subject VARCHAR(50) NOT NULL,
	year Int(5) NOT NULL,
	age Int(5) NOT NULL,
	gender char(10) NOT NULL,
	birth Date NOT NULL,
	contact VARCHAR(15) NOT NULL,
	email VARCHAR(100) NOT NULL,
	PRIMARY KEY ( contact )
);
DROP TABLE STUDENT_REGISTER;
