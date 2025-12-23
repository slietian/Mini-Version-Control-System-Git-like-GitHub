# Mini Version Control System (Git-like)

A lightweight Git-like version control system built from scratch to understand how Git works internally.  
This project implements core version control features using low-level file system operations and hashing.

---

## Project Overview

This project replicates fundamental Git functionality to demonstrate how version control systems manage files, commits, and history internally without using Git libraries.

Key focus areas:
- File system based storage
- Content-addressable objects
- Commit tracking and history
- Hash-based integrity

---

## Features

- Initialize a repository (`init`)
- Stage files (`add`)
- Create commits (`commit`)
- View commit history (`log`)
- SHA-1 based object storage
- Directory-based repository structure

---

## Tech Stack

- Language: Python
- Concepts:
  - File System Operations
  - SHA-1 Hashing
  - Object Storage
  - Command-Line Interface
  - Data Integrity

---
mini-git/
│
├── .mygit/
│ ├── objects/
│ ├── refs/
│ └── HEAD
│
├── commands/
│ ├── init.py
│ ├── add.py
│ ├── commit.py
│ └── log.py
│
├── utils/
│ ├── hash_utils.py
│ └── file_utils.py
│
├── main.py
└── README.md


---

## Usage

### Initialize Repository
```bash
python main.py init

Add Files
python main.py add <filename>

Commit Changes
python main.py commit "commit message"

View Commit History
python main.py log

Key Learnings

How Git stores data internally

Difference between working directory, staging area, and commits

Hash-based content tracking

Low-level backend and storage design

Version control system fundamentals

Reference

Inspired by the CodeCrafters challenge:
https://github.com/codecrafters-io/build-your-own-git

This implementation is an independent educational project.

Future Enhancements

Branch support

Merge functionality

Diff viewer

Improved CLI interface
## Project Structure

