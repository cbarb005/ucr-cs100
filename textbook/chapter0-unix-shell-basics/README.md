#Chapter 0: Unix Shell Basics

This chapter covers the basic concepts and tools you will need in order to understand how to write a simple command line shell.  

##Section 0 : system calls
This section covers three basic system calls that will be used in the homework assignment, as well as an error-checking function.

perror: provides error-checking for your system calls (a requirement throughout the course).

fork: creates copies of the parent process, or "child" processes, necessary to execute commands from the command line.

wait: allows program to wait for child processes to finish executing before continuing.

exec: executes executables. 

##Section 1 : parsing
This section covers a couple of parsing tools that may be useful for your homework assignment

strtok: C library function to tokenize, or break apart, a c-string based on your specifications.

boost tokenizer: Boost library class that tokenizes strings.

##Section 2 : Makefile
This section covers how to write Makefiles.

make: compiles and installs programs easily, exactly as your Makefile specifies.

##lab0 - vim

Introduces Vim, the text editor of choice for the class, and how to navigate it. Learn how to configure your .vimrc file to your liking. 

##lab1 - git

Practice with using git for version control, creating and forking repositories to your local machine, updating repositories, and sharing them through github.

##HW0 - Rshell

Write your own basic Unix shell to execute simple commands with parameters, and to handle connectors.
