#  SQLite Database Management System using Python

A beginner-friendly, menu-driven **CRUD application** built using **Python** and **SQLite**. This project demonstrates the use of Object-Oriented Programming (OOP) for managing personal data including name, age, gender, address, contact, and mail.

---

##  Features

-  Insert new records
-  Fetch and display all records
-  Update specific fields (name, age, gender, etc.)
-  Delete records by ID
-  Automatically creates database and table on first run
-  Uses OOP principles for modular and reusable design

---

## 🛠 Technologies Used

| Technology     | Purpose                          |
|----------------|----------------------------------|
| Python         | Programming language             |
| SQLite         | Lightweight embedded database    |
| `sqlite3`      | Python library to connect SQLite |

---

##  Database Schema

The program automatically creates a database file named `Sqlitedatabase.db` with a table called `datas`:

```sql
CREATE TABLE datas (
  id INTEGER PRIMARY KEY,
  name TEXT NOT NULL,
  age INTEGER NOT NULL,
  gender TEXT NOT NULL,
  address TEXT NOT NULL,
  contact TEXT NOT NULL,
  mail TEXT NOT NULL
);
