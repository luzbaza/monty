
## 0x19. C - Stacks, Queues - LIFO, FIFO

Learning Objectives
At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General
* What do LIFO and FIFO mean
* What is a stack, and when to use it
* What is a queue, and when to use it
* What are the common implementations of stacks and queues
* What are the most common use cases of stacks and queues
* What is the proper way to use global variables

## Requirements

### General
* Allowed editors: vi, vim, emacs
* All your files will be compiled on Ubuntu 14.04 LTS
* Your programs and functions will be compiled with gcc 4.8.4 using the flags -Wall -Werror -Wextra and -pedantic
* All your files should end with a new line
* A README.md file, at the root of the folder of the project is mandatory
* Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl
* You allowed to use a maximum of one global variable
* No more than 5 functions per file
* You are allowed to use the C standard library
* The prototypes of all your functions should be included in your header file called monty.h
* Don’t forget to push your header file
* All your header files should be include guarded
* You are expected to do the tasks in the order shown in the project

## Data structures
![Readme](https://user-images.githubusercontent.com/71143825/118015323-c6745880-b319-11eb-994e-a11398815d1b.PNG)
![otro](https://user-images.githubusercontent.com/71143825/118015577-0e937b00-b31a-11eb-9d62-1808345bb237.PNG)

## Compilation & Output
* Your code will be compiled this way:
![image](https://user-images.githubusercontent.com/71143825/118015841-55817080-b31a-11eb-8d64-8c82e506909b.png)

## The Monty language
Monty 0.98 is a scripting language that is first compiled into Monty byte codes (Just like Python). It relies on a unique stack, with specific instructions to manipulate it. The goal of this project is to create an interpreter for Monty ByteCodes files.

### Monty byte code files

Files containing Monty byte codes usually have the .m extension. Most of the industry uses this standard but it is not required by the specification of the language. There is not more than one instruction per line. There can be any number of spaces before or after the opcode and its argument:


