This project designs and implements a relational database for a university library system to track books, authors, publishers, students, and employees.

The database schema consists of the following tables:
<img width="811" alt="Screenshot 2024-09-30 at 11 27 06 PM" src="https://github.com/user-attachments/assets/5be8dcb2-cfe6-43d5-adb6-7570c3071552">

BOOK - Contains book ID, name, page count, ISBN, and foreign keys

AUTHOR - Stores author ID, name, address, and email

PUBLISHER - Stores publisher ID, name, address, and email

STUDENT - Stores student ID, name, address, and email

EMPLOYEE - Stores employee ID, name, address, and email

BOOK_AUTHOR - Mapping table for books and authors

Key constraints and relationships:
Primary keys on ID fields for each main entity table

Foreign keys from BOOK to STUDENT, EMPLOYEE, and PUBLISHER

Mapping table BOOK_AUTHOR for many-to-many relationship between books and authors
