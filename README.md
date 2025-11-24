# Java Library Management System (GUI + MySQL)

A desktop-based Library Management System built with Java Swing and MySQL. It helps librarians manage books and members, and track book borrowing and returns through a clean GUI.

## Features

- Add and view books with title, author, ISBN, genre, and availability status.
- Add and view library members with name and email.
- Search books by title, author, or genre from the Member tab.
- Issue (borrow) and return books, with transaction history per member.
- Book availability automatically updates based on borrow/return status.
- Login screen with user validation from a `users` table (admin / librarian login).
- MySQL database integration using JDBC, PreparedStatement, and transactions.
- Background loading of data using SwingWorker to keep the UI responsive.
- Modern UI using FlatLaf theme, titled borders, and improved layout.
- Small dashboard stats showing total, available, and issued books.

## Tech Stack

- Java (Swing)
- MySQL
- JDBC (MySQL Connector/J)
- FlatLaf Look and Feel

## How to Run

1. Import the project into IntelliJ IDEA.
2. Create a MySQL database named `library_db` and run the provided SQL scripts to create tables.
3. Update the DB credentials in `DBConnection.java` if needed.
4. Build and run the `main` class.
5. Log in with the default user: `admin / admin123`.

