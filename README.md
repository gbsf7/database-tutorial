[![GDSC](https://i.postimg.cc/qRP6BRqZ/GDSC-Database-Horizontal-color.png)](https://gdsc.community.dev/universitas-sultan-ageng-tirtayasa/)
# GDSC Database Learning Path

## Chapter 1 - Prerequisite
1.	What is Database ?  *`(Working on Scripts to read)`*
    - SQL (Sequel)
    - NoSQL
2.	What is MySQL ?
3.	What is Xampp ?
4.	Installing MySQL. (Two Options, XAMPP or Straight thru MySQL Website) *`(XAMPP Easiest, from MySQL Website a bit longer)`*
5.	Creating our first Database
6.	Creating our first Table
## Chapter 2 – CRUD Implementation | Longest one by far.
7.	What is CRUD ? *`(Should i add API ?)`*
8.	CRUD Example in other application
9.	CRUD in SQL
10.	Inserting Data to our Table
11.	SELECT(Reading Data) in our Table
	- Adding parameters to or SELECT args
	- WHERE parameter
	- AND, or, NOT parameter
    - IN parameter
    - BETWEEN parameter
    - LIKE parameter
    - REGEXP parameter
    -	IS NULL parameter
    -	ORDER BY parameter
	- LIMIT parameter
12. Updating Data in our table 
13. Deleting Data in our Table
## Chapter 3 – Table Join
### Chapter 3 Part One
14.	Joining Table 
	  - INNER JOIN
	  - Joining Across Databases
	  - SELF JOIN
	  - Joining Multiple Tables
	  - COMPOUND JOIN – Implicit Join
	  - OUTER JOIN
	  - Between Multiple Table 
	  - SELF OUTER JOIN
	  - USING Clause
	  - NATURAL JOIN
	  - CROSS JOIN
	  - UNION
### Chapter 3 Part Two - Column Attributes.
15.	Column Attributes
16.	Inserting Single Row
17.	Inserting Multiple Rows
18.	Inserting Hierarchical Rows
19.	Copying table
20.	Updating Single Row
21.	Updating Multiple Rows
22.	Using Subqueries in Updates
23.	Deleting Rows


# Installing MySQL
There are two ways to install MySQL Database, first is to use XAMPP Installer, or Second is to use the Official MySQL Community Server Installer from MySQL Page

## XAMPP
### Getting Started
First you need to download XAMPP installation files from the official [XAMPP Download Page](https://www.apachefriends.org/download.html), then run the Installer.

![XAMPP](https://i.postimg.cc/K8s6qnrx/image.png)

_Do note that XAMPP needs write permission if you want to use XAMPP MySQL, the installer SHOULD prompt you that it's better to not put XAMPP files in the C: Directory so install it elsewhere to avoid unecessary problems._

After it's done, you should be prompted if you wanna open XAMPP Control Panel, Check the box and click finish

in the Control Panel, Start the apache and MySQL module

![XAMPP_Control_Panel](https://i.postimg.cc/6qFKmgvV/image.png)

Then open [PHPMyAdmin](http://localhost/phpmyadmin) or type localhost/phpmyadmin in your browser.

Installation is Done!

## MySQL Community Server Installer
### Getting Started
First you need to download MySQL Community Server Edition from [MySQL Download Page](https://dev.mysql.com/downloads/windows/installer/8.0.html)

The Installer should guide you through the installation, choose all default option. When it's done, you can access it using [MySQL Workbench](https://dev.mysql.com/downloads/workbench/)


