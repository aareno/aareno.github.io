---
layout: project
type: project
image: img/database.png
title: "Record Database"
date: 2022
published: true
labels:
  - C++
  - ICS211
summary: "A record database that stores a users name, address and account number."
---

Something Something

Here is some code that shows how I got the users address:

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
