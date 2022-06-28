# EXAM RANK 04

### Third exam in the 42 cursus. On it we must create a C program named microshell to execute some shell commands. You can find more information en the [subject](Subject/subject.en.txt). Some important tips on it are; 
#### · This program must manage | (pipes) to communicate commands and ; (semicolon) to separate independent commands just like in bash.
#### · It do not manage any wildcard or enviroment variables.
#### · You must create your own cd built-in with some concrete funtions on it (excluded - or cd alone).
#### · No file descriptor leaks are allowed.

### To execute it you must;
#### · Open your terminal.
#### · Compile the project with "gcc microshell.c -o microshell"
#### · Execute the commands with the complete route for each command, for example:
####      ./microshell /bin/ls "|" /usr/bin/grep microshell ";" /bin/echo i love my microshell
####      This command must return:
####        microshell
####        i love my microshell

### Graded: [![fballest's 42 Exam Rank 04 Score](https://badge42.vercel.app/api/v2/cl45d74de005409l9l5r3ozl6/project/2504175)](https://github.com/JaeSeoKim/badge42)
