Title: Library Management System — Project Proposal
Name: Manmeet Singh
Course: CS-1103
Date: March 4, 2026

1) Application Overview
I will design and implement a relational database for a Library Management System. The database will store members, books, authors, copies of books, and loan transactions (borrowing/returning). The purpose is to
support searching books, checking availability, borrowing, returns, and overdue tracking. 

2) Initial Entities & Relationships (draft schema)
Entities (tables): Member, Book, Author, Copy
Relationship tables: BookAuthor (Book↔Author many-to-many), Loan (Member borrows a Copy)

3) Dataset Plan 
I will use synthetic sample data created using INSERT statements (e.g., ~30 members, ~40 books, ~60 copies, ~80 loans). 

4) Information/Insight to Mine + Use
I will query: most borrowed books/authors, overdue loans, and book availability. These insights help track usage trends and manage inventory.

5) GitHub Repository
https://github.com/manmeet-1195/CS1103-Project
