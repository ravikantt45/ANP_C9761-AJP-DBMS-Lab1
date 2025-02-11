CREATE DATABASE Infosys; #Database created as INFOSYS
USE Infosys;
CREATE TABLE employee ( #Employee Table created 
    e_id INT PRIMARY KEY,
    e_name VARCHAR(50)
);
DESC employee; #Display the Table 


# Operations On The Created table
ALTER TABLE employee RENAME TO emp_personel_detail; 
DESC emp_personel_detail;

ALTER TABLE emp_personel_detail ADD place VARCHAR(50);
DESC emp_personel_detail;

ALTER TABLE emp_personel_detail CHANGE place e_place VARCHAR(50);
DESC emp_personel_detail;

ALTER TABLE emp_personel_detail MODIFY e_name VARCHAR(100);
DESC emp_personel_detail;

ALTER TABLE emp_personel_detail ADD e_email VARCHAR(100);
DESC emp_personel_detail;

ALTER TABLE emp_personel_detail DROP COLUMN e_email;
DESC emp_personel_detail;

ALTER TABLE emp_personel_detail ADD e_yoe INT;
DESC emp_personel_detail;

#Inserting the Data

INSERT INTO emp_personel_detail (e_id, e_name, e_place, e_yoe) VALUES
(101, 'Ramu', 'Mysore', 3),
(102, 'Raju', 'Bangalore', 4),
(103, 'Rani', 'Chennai', 3),
(104, 'Sam', 'Hyderabad', 2),
(105, 'Raja', 'Madurai', 1),
(106, 'Ramya', 'Trichy', 0),
(107, 'Selvi', 'Bombay', 3),
(108, 'Kalyani', 'Bangalore', 7),
(109, 'Tom', 'Mysore', 4),
(110, 'Vasu', 'Chennai', 5);

#Inserting The Data

INSERT INTO emp_personel_detail (e_id, e_name, e_place, e_yoe) VALUES
(111, 'John', 'Pune', 2),
(112, 'David', 'Delhi', 6),
(113, 'Anita', 'Mumbai', 5);
SELECT * FROM emp_personel_detail;

INSERT INTO emp_personel_detail (e_id, e_name, e_place) VALUES
(114, 'Sita', 'Goa'),
(115, 'Mohan', 'Kolkata');
SELECT * FROM emp_personel_detail;

#Updating the existing value
    
UPDATE emp_personel_detail SET e_yoe = 0 WHERE e_yoe IS NULL;
SELECT * FROM emp_personel_detail;

#Performing Deletion Operation on employee id is 105
    
DELETE FROM emp_personel_detail WHERE e_id = 105;
SELECT * FROM emp_personel_detail;

DELETE FROM emp_personel_detail WHERE e_yoe < 2;

SELECT * FROM emp_personel_detail;   #diplay all records after all the operations
