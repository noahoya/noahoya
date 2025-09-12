---
layout: project
type: project
image: img/C.png
title: "Java & C Integration with JNI"
date: 2024
published: true
labels:
  - C
  - Java
  - JNI
  - Make files
summary: "Program from ICS 212 that used two languages for front end and back end"
---

Created a cross-language application that generates a formatted table of numbers and checks whether each value is a multiple of three. The Java front-end handled user input and table display, while the C back-end handled the mathematical logic, connected through the Java Native Interface (JNI). This allowed me to develop skills in software interoperability and modular design by integrating two programming languages. Showcased the ability to bridge systems-level logic with higher-level interfaces.

Here is a snippet of a script recording user inputs and how the application responded
Script started on Fri 13 Sep 2024 10:41:27 PM HST
]0;noahoya@uhx02:~/homework2 [?1034huhx02:/home/n/noahoya/homework2% exitgcc -o homework2 homework2.oansi -pedantic-errors -Wall -c homework2.c
[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[C[Cexit[K./homework2
This program will generate a table of numbers from
0 to the maximum number you(the user) provide(s)
It will also have a column stating whether each
number is a multiple of 3 or not.
Enter maximum number to show: -5
Please enter a valid positive integer.
This program will generate a table of numbers from
0 to the maximum number you(the user) provide(s)
It will also have a column stating whether each
number is a multiple of 3 or not.
Enter maximum number to show: abc
Please enter a valid positive integer.
This program will generate a table of numbers from
0 to the maximum number you(the user) provide(s)
It will also have a column stating whether each
number is a multiple of 3 or not.
Enter maximum number to show: 15
  Number  Multiple of 3?
       0  No
       1  No
       2  No
       3  Yes
       4  No
       5  No
       6  Yes
       7  No
       8  No
       9  Yes
      10  No
      11  No
      12  Yes
      13  No
      14  No
      15  Yes
]0;noahoya@uhx02:~/homework2 uhx02:/home/n/noahoya/homework2% exit
exit

Script done on Fri 13 Sep 2024 10:41:44 PM HST
