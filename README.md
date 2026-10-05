# Adaptive Password Manager Using Optimized Hash Tables

## 📌 Project Description

A Data Structures project that manages passwords efficiently using an optimized **Hash Table** with **Quadratic Probing** for collision handling and **Dynamic Resizing** for better performance.

## 🚀 Features

* Add password records
* Search passwords quickly
* Update existing passwords
* Delete password records
* Display all saved records
* Handle hash collisions using Quadratic Probing
* Automatically resize the hash table
* Display hash table statistics

## 🧠 Data Structures Used

* Hash Table
* Structure
* Dynamic Memory Allocation
* Quadratic Probing

## ⚙️ Technologies

* Language: **C**
* Compiler: GCC / MinGW
* Platform: Windows / Linux

## 🔄 How It Works

1. User enters website, username, and password.
2. The website name is passed to the hash function.
3. The hash function generates an index.
4. The record is stored in the hash table.
5. If a collision occurs, Quadratic Probing finds another position.
6. When the load factor exceeds 70%, the table automatically increases in size.
7. Existing records are rehashed into the new table.

## 📊 Operations

| Operation | Average Complexity |
| --------- | ------------------ |
| Insert    | O(1)               |
| Search    | O(1)               |
| Update    | O(1)               |
| Delete    | O(1)               |
| Resize    | O(n)               |

## ▶️ How to Run

### Compile

```bash
gcc password_manager.c -o password_manager
```

### Run

Windows:

```bash
password_manager.exe
```

Linux:

```bash
./password_manager
```

## 📋 Menu

```text
1. Add Password
2. Search Password
3. Update Password
4. Delete Password
5. Display All Passwords
6. Hash Table Statistics
7. Exit
```

## 🎯 Project Objective

The main objective is to demonstrate how **Hash Tables** can be used for fast data storage and retrieval while improving performance through **collision resolution and adaptive resizing**.

## ⚠️ Note

This project is an educational prototype. Passwords are stored in plain text to demonstrate Data Structures concepts and should not be used for storing real passwords.

## 👨‍💻 Project Type

**Data Structures Course Project**
