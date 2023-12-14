---
layout: project
type: project
image: img/database.png
title: "Record Database"
date: 2022
published: true
labels:
  - C++
  - ICS212
summary: "A record database that stores a users name, address and account number."
---

## Overview

In this project, I created a database that stores a record (a users name, address and account number). The program opens with a user interface asking what the user wants to do (remove a record, read a record, or add a record). 

This is what the user interface does if you start the program:

```cpp
Hello! Welcome to the bank!

Please select an option:

add: (add a record)
remove: (remove a record)
read: (read a record)
printall: (prints all records)
quit: (quit the program)


```

## How it works

This program uses C++ File I/O classes to read and write into a text file. The text file acts as a database for the records. At the beginning of the program, it reads a text file to checks if their are any records, if there are, it adds them to the database. Next, The UI is presented and if the user selects add, the program asks the users for their data and adds it to the database. If the user selects remove, they can remove a record from the database. If the user selects read they can read a record from the database. If they select print all, they can print all the records in the database. While the program is running, the user can create any change they want to the database. Whenever the program is closed, the changes are written to the text file and will show up the next time the program is opened. 

Here is the code on how I asked for the users address:

```cpp
void getAddress(char address[], int size)
{

  cout << "Please enter your address: \n";
  cout << "Enter a ( / ) at the end of address";

  cin.get(address, size, '/');
  cin.get();
  cin.get();

}
```
