---
title:  "Lesson 2. Writing The First Program"
date:   2021-03-11 20:58:00
categories:
- Learn Programming
- Programming
- 2021 Programming
tags:
- C
- Xcode
- Algorithm
- Grade 13
- Learn Programming
- Computer Science
---
# Overview
* Write your first C/C++ Program

# Before we start
I will be using Xcode 12.4 on macOS 11.2.3, running on intel-based MacBook Pro 13 inch 2019. Due to the odd nature of visual studio's C compiler, some codes might not work on them. I highly recommend using online IDE using gcc compiler.

# Start to code!
## Launch Xcode
When you launch Xcode, you will see the screen like this:
<img width="486" alt="Xcode 1" src="https://user-images.githubusercontent.com/46326335/110869105-c9aa8400-8297-11eb-9935-6e96eb99135d.png">

## Create a new Xcode project
When you press on "Create a new Xcode project", you will be asked to choose the type of the project. There is an option called "Command Line Tool" under macOS tab.
<img alt="Xcode 2" src="https://user-images.githubusercontent.com/46326335/110877785-f6669780-82a7-11eb-8de8-292b6933af18.png">
After that, name your new project and put Organization Identifier you want (I have it as "Personal"). Also you should select the programming language as C.

## Start coding
On the side bar, there will be a file called main.c. If you click on it, you will be able to start coding!
<img alt="Xcode 3" src="https://user-images.githubusercontent.com/46326335/110877951-4fcec680-82a8-11eb-9272-cf3abba876ef.png">

# Coding
## What are we going to make our program to do?
Since this would be the very first writing the C code, we will begin with printing something to the screen.
## Procedure
1. Erase everything from the screen
2. Type ```C
#include <stdio.h>
int main() {
  printf("Very first program I wrote in C!");
  return 0;
}
```
