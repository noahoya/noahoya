---
layout: project
type: project
image: img/C.png
title: "Bank Database Application"
date: 2024
published: true
labels:
  - C
  - C++
  - Linked Lists
  - File I/O
  - Object-Oriented Programming
summary: "Program from ICS 212 allowed a user to maintain bank records"
---

Overview
This project focused on developing a banking database system that allows users to add, delete, search, and display customer records. The goal was to simulate a simple bank database with persistent storage and provide a user-friendly interface for performing basic operations. The initial version was implemented in C using a sorted linked list to manage records, which required careful handling of dynamic memory allocation and pointer operations.

Implementation
I later refactored this project into C++ to take advantage of object-oriented programming concepts such as encapsulation and constructors/destructors. This version introduced a class (llist) to manage the database, improving code readability and maintainability. I also added a debug mode that prints function calls and parameters to assist with tracing and testing. The project required separate compilation and linking with a Makefile, which taught me how to structure larger programs into multiple source files.

Outcome
Through this project, I gained experience with low-level memory management, linked list manipulation, file I/O, and OOP design principles. This was my first project that truly felt like building a small-scale software product rather than just writing a program.

Here is a snippet of the code for when a user wanted to add an account:

 if (strncmp(user_input, "add", strlen(user_input)) == 0)
        {
            printf("Please provide the account number and press enter: ");
            user_input_accountNum = scanf("%d", &accountno);
            fgets(trash, 100, stdin);

            if (user_input_accountNum != 1 || accountno <= 0)
            {
                printf("Please enter a valid positive integer.\n");
                valid_input = 0;
            }
            
            if(valid_input)
            {
            printf("Please enter the name for the account: ");
            fgets(name, 30, stdin);
            name[strcspn(name, "\n")] = 0;
            printf("Please enter the Address and enter '!' when finished:\n");
            getaddress(address, 45);
            addRecord(&start, accountno, name, address);
            fgets(trash, 100, stdin);
            }
        }
