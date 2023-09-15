---
layout: project
type: project
image: ../img/bank-database/C++.png
title: "Bank Database"
date: 2023
published: true
labels:
  - C++
summary: "A program written in C++ used to perform bank database operations such as storing, viewing, or removing bank records."
---

<img class="img-fluid" src="../img/bank-database/bank-database.png>

For a previous course I've taken, ICS 212 - Program Structure, the class was given a project to implement a database for a bank. The goal of this was to create and simulate a database program from both the user interface side and the database side. Using everything that was taught about classes, pointers, memory allocation, data structures, and traversing them in C++, this project would essentially tie all of that together to mirror a real world application where many interactive databases are used.

For the front end, a simple command line user interface was created to allow the user to interact with the program by providing values for selecting options, and passing in data that will be stored in the records in the database. As for the back end, a linked list data structure was used to store all the records. Each record stores an account number, name of the customer, address of the customer, and a pointer to the next record. The records would be sorted by their account number in ascending order. The program supported the following operations on the records:
<ol>
    <li>Add a record</li>
    <li>Find a record</li>
    <li>Print all records</li>
    <li>Delete a record</li>
</ol>

From this project, I gained somewhat of a bird's eye view of what programs similar to this project might look like in the real world. Beyond the learning of C++ syntax, classes, and pointers, I've picked up on concepts to keep in mind to make programs "better," such as information hiding and proper memory management.