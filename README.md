# Library Management System in C++

This is a console-based Library Management System developed using Object-Oriented Programming (OOP) principles in C++. It is designed to manage library resources, including books and members, and perform common library operations efficiently.

## Overview

The project models key entities involved in a library system:

- **Books**: Representing library resources with attributes such as title, author, ISBN, and availability status.
- **Members**: Library users who can borrow and return books.
- **Library Staff**: Users with permission to add, remove, or update book records.

This system serves as a practical application of OOP concepts in a real-world context.

## Key OOP Concepts Implemented

- Encapsulation through class design
- Inheritance (e.g., `Member` and `Staff` classes derived from a common `User` class)
- Polymorphism for extending behavior
- Composition to associate books with members
- Static members for tracking total book count or unique IDs
- Friend functions for internal data access when needed

## Features

- Add, update, and remove books from the system
- Register new members and manage their information
- Borrow and return books with status tracking
- Display available and issued books
- Generate simple activity reports
- Search books by title, author, or ISBN

## License
This project is for academic and learning purposes. You’re free to use or modify it with credit.

---
