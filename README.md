# Library Management System

A Python-based Library Management System with user roles, book borrowing, and persistent JSON storage.

## Features

### User Management
- Register new users with secure password policy
- Login system
- Password recovery via security question
- Auto-generated unique User IDs
- Default admin account (`admin` / `Admin123`)

### Book Management
- Add new books (admin only)
- Remove books (admin only)
- Search books by title, author, or year
- List all available/borrowed books

### Borrowing System
- Borrow books (return in 14 days)
- Return borrowed books
- Renew books once (extend by 7 days)
- Suggest a random available book

### Roles
- **User**: can search, list, borrow, return, renew, get suggestions
- **Admin**: all user abilities + add/remove books and list users

### Storage
- Users stored in `users.json`
- Books stored in `books.json`

## How to Run
--- Library Management System ---
1. Login
2. Register
3. Recover Password
4. Exit
Choose an option: 1
**** Login ****
Username: admin
Password: Admin123
Welcome, admin!

**** Admin Menu ****
1. Add New Book
2. Remove Book
3. Search Books
4. List All Books
5. Borrow Book
6. Return Book
7. Renew Book
8. Suggest Random Book
9. List Users
10. Logout

```bash
python library_system.py
