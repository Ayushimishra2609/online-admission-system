# Online Admission System 🎓

This is a Java-based desktop application built using NetBeans and MySQL for managing online student admissions.

## 💻 Tech Stack
- Java (Swing, JDBC)
- NetBeans IDE
- MySQL Database

## 🔐 Features
- Admin login
- Student registration form
- Admission form validation
- Database connectivity with MySQL

## 🗄️ Database Setup
1. Import `userdatabase.sql` into your MySQL server.
2. Update DB config in code if needed:
   ```java
   Connection connection = DriverManager.getConnection("jdbc:mysql://localhost:3306/userdatabase", "root", "Ayushi2609@@");
