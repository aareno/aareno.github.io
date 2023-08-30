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

In this project, I created a database that stores a users name, address and account number. The program opens with a user interface asking what the user wants to do (remove a record, read a record, or add a record). 

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


The program asks the users for their data and stores it insde a text file. The text file changes whenever the user adds or removes data using the program and the is saved everytime the user quits out of the program. 

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
