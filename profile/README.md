# CS 344 - Operating Systems

## Course Description
Introduction to operating systems using UNIX as the case study. System calls and utilities, fundamentals of processes and interprocess communication. 

## Notable Projects
[**Assignment 3:**](https://github.com/CS-344-jackhart/Assignment-3) This assignment asked us to create a "small" shell. In order to
do this, I parsed input into a command struct I created, and then either executed my own commands I made (cd, status, exit), or asked the shell to
execute it for me using the family of exec functions in C. In this assignment, I also implemented background processes and signal handling for SIGINT and
SIGTSTP. 

[**Assignment 5:**](https://github.com/CS-344-jackhart/Assignment-5) For this assignment, we were tasked with creating two clients and two servers. One client and one server would be responsible for encrypting a file and the other two were responsible for decrypting. This was done using the C Berkley sockets API and OTP encryption. 
