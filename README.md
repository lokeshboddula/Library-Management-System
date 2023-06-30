# Library-Management-System

Environment and Requirement : 
Programming Language: JAVA with Swing
MySQL Conncector: MySQL JConnector (JDBC Driver) https://dev.mysql.com/downloads/connector/j/
IDE: NetBeans
MySQL 
MySQL WorkBench

About Files
/SQL: Contains the Exported Database Schema
/src/mainlibrary: Contains JAVA source codes
/MySQL Connector: Contains JDBC/MySQL JConnnector

Instructions
Clone the Project using link https://github.com/lokeshboddula/Library-Management-System.git or Download the zip

Importing Java Project in NetBeans
Clone the project in the NetBeans 
NetBeans->Team->Git->Clone and copy-paste this repo link
Importing Database(Schema)
Import the Database in the MySQL database using MySQL WorkBench
MySQL Workbench->Data Import/Restore->Load Folder Contents->SQL
Connect the JDBC driver(JConnector) by including the it's JAR File in the Project
Expand Project->Libraries->(Right Click)ADD JAR File->include file: mysql-connector-java-5.1.40-bin.jar
Database setting can be changed
