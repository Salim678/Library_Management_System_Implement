# 📚 Library Management System (Java + MySQL + Swing)

A fully-featured, GUI-based Library Management System built in Java using Swing for the interface and MySQL for the database. This system enables book and member management, issue/return operations, real-time dashboard analytics, PDF export, and more — all designed using best practices in software development.

---

📂 Project Structure

LibraryManagementSystem/ • src/main/java/lms/gui/

 - MainFrame.java

 - BookPanel.java

 - StudentPanel.java

 - IssuePanel.java

 - ReturnPanel.java

 - DashboardPanel.java

• src/main/java/lms/db/

 - DBConnection.java

• src/main/java/lms/model/

 - Book.java

 - Student.java
   
 - Transaction.java

• src/main/java/lms/dao/

  - BookDAO.java

  - StudentDAO.java

  - TransactionDAO.java

• src/main/java/lms/util/

 - Validator.java
 
 - PDFExporter.java
 
 - ChartHelper.java
 

• lib/

  - mysql-connector-java.jar

  - pdfbox.jar

• LMS.sql – MySQL database schema

• LMS.jar – Executable JAR file

• README.md – Project documentation

• LMS_Documentation.docx – Full report and guide

---


## 🚀 Features

- 📖 **Book Management**: Add, view, delete, update books
- 👤 **Member Management**: Add, view, delete, update members
- 🔁 **Issue/Return**: Manage borrow/return with dates
- 📊 **Dashboard**: Real-time metrics of total, issued, and available books
- 📄 **PDF Export**: Generate printable reports for books and members
- 🛡️ **Validation**: Email checks, empty field detection, duplicate entry prevention
- ✅ Data validation & exception handling
- 🧩 Modular architecture (MVC + DAO)

---  

                          Input
## ✅ Project Guidelines Followed

| Guideline

| ✔ Core Feature Implementation 

| ✔ Error Handling & Robustness

| ✔ Component Integration

| ✔ Event Handling & Processing

| ✔ Data Validation

| ✔ Code Quality & Innovation

| ✔ Project Documentation


| Implementation Summary


| Try-catch blocks, user alerts, DB exception logging

| DAO, GUI, Models connected through Controller logic

| Optimized event listeners, Swing event delegation

| Field checks (client-side) + DB constraints (server-side)

| Modular OOP, MVC pattern, PDF export, dashboard analytics 

| docs/index.md, setup guide, feature list, and usage 


---

## 🛠️ Technologies Used

-   Java (JDK 8+)
-   Swing (for GUI)
-   MySQL (as RDBMS)
-   JDBC (for database connectivity)
-   iText (for PDF generation

---
