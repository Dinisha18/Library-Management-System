# Library-Management
This is a Library Management Website built using HTML, CSS, Javascript, PHP and MySQL for Sophomore Year project of Web Technology.
HOW TO SETUP :
1. Fork this project and create a clone in your system.
2. Now Save the Code1 Folder in your htdocs folder of XAMPP.
3. Now lets' setup our database.
4. Create a Database named library_db in PHPMyAdmin.(Ensure that you have connected PHPMyAdmin to MySQL once before otherwise it won't open)
5. Now run following code in library_db database:
6.  create table admin(
    adminId int NOT NULL AUTO_INCREMENT PRIMARY KEY,
    adminName varchar(50) NOT NULL,
    password varchar(50) NOT NULL,
    username varchar(50) NOT NULL,
    email varchar(50) NOT NULL
    );
    
create table books(
    bookId int NOT NULL AUTO_INCREMENT PRIMARY KEY,
    bookTitle varchar(50) NOT NULL,
    author varchar(50) NOT NULL,
    label varchar(50) NOT NULL,
    publisherName varchar(50) NOT NULL,
    categories varchar(50) NOT NULL,
    callNumber varchar(50) NOT NULL
    );
    
create table students(
    studentId int NOT NULL AUTO_INCREMENT PRIMARY KEY,
    email varchar(50) NOT NULL,
    name varchar(50) NOT NULL,
    department varchar(50) NOT NULL,
    phoneNumber varchar(50) NOT NULL
    );  
    
create table borrow(
    borrowId int NOT NULL AUTO_INCREMENT PRIMARY KEY,
    borrowDate varchar(50) NOT NULL,
    returnDate varchar(50) NOT NULL,
    studentId varchar(50) NOT NULL,
    bookId varchar(50) NOT NULL
    );

7. This will create tables named admin, books, students and borrow in library_db database.
8. Now add data of first user in admin table so that you can log-in into the website. (*And not get stuck on first page 😂*)
9. Now open the website by typing https://localhost/code1/admin.php in your browser.

For any further questions email me at dagarwal7189@gmail.com.

Have Fun!!
