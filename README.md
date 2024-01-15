# JavaDBMS

JavaDBMS is a simple and customizable Database Management System implemented in Java. It uses a linked list data structure to manage student information.

## Table of Contents
- [Features](#features)
- [Supported Queries](#supported-queries)
- [Usage](#usage)
- [How to Contribute](#how-to-contribute)
- [License](#license)

## Features

- Insert, update, and delete records
- Basic SQL-like queries (select, count, sum, avg, max, min)
- Linked list-based storage for student information
- Simple and lightweight

## Supported Queries

1. Insert: `insert into student values('Amit','Pune',78);`
2. Select All: `select * from student;`
3. Select with Condition: `select * from student where City = '_____';`
4. Count: `select Count(Marks) from student;`
5. Sum: `select Sum(Marks) from student;`
6. Average: `select Avg(Marks) from student;`
7. Maximum: `select Max(Marks) from student;`
8. Minimum: `select Min(Marks) from student;`
9. Select by Name: `select * from student where name = "_____";`
10. Update: `update student set City = "___" where Rno = ____;`
11. Delete: `delete from student where Rno = ___;`

## Usage

1. Compile the Java files:
   ```bash
   javac VirtualDBMS.java
