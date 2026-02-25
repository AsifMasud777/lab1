
CREATE DATABASE clp
CREATE TABLE COUNTRY(
     country_id int not NULL,
  country_id INT,
   
    country_name varchar(50),
    continent varchar(50),
    Currency varchar(50)
    );
   
    CREATE TABLE DEPARTMENT(
        DeparmentId int not NULL,
        DepermentId INT,
        DepartmentName varchar(50),
        CountryId INT
       
        );
       
     CREATE TABLE EMPLOYEE(
         EmpId int not NULL,
         EmpId INT,
         EmpName varchar(50),
         DepId varchar(50)

         );
         
     CREATE TABLE FOLDER(
         Folder int not  NULL,
         Folderid INT,
         Emplyid INT,
         AccessType varchar(50)
         
         );
   
    INSERT into COUNTRY VALUES (242,"CSE","SOUTH","taka");
    INSERT into COUNTRY VALUES (2421,"usa","north","dolar");
INSERT into COUNTRY VALUES (2422,"india","south","rupi");
INSERT into COUNTRY VALUES (24233,"oman","south","dinhar");
INSERT into COUNTRY VALUES (24244,"spain","Europ","euro");
USE TABLE;
SELECT * FROM   COUNTRY;

INSERT into DEPARTMENT VALUES (222,"cse",2211);

INSERT into DEPARTMENT VALUES (211,"EEE",2111);

INSERT into DEPARTMENT VALUES (200,"BBA",2011);

INSERT into DEPARTMENT VALUES (122,"MBA",1211);

INSERT into DEPARTMENT VALUES (112,"Physics",1111);






INSERT into EMPLOYEE VALUES (22221,22111,"DEFOLT");
INSERT into EMPLOYEE VALUES (2223,"SCHOOL",22112);
INSERT into EMPLOYEE VALUES (2224,"COLLAGE",22113);
INSERT into EMPLOYEE VALUES (2225,"UNIVERSITY",22114);
INSERT into EMPLOYEE VALUES (2226,"SHOP",22115);


INSERT into FOLDER VALUES (222,"cse",2211);


 


