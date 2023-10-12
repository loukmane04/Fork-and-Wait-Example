# Fork-and-Wait-Example
This C program demonstrates the usage of the fork() system call to create a child process and the wait() function to make the parent process wait for the child process to complete.

# Prerequisites
Make sure you have a C compiler installed on your system. You can use GCC (GNU Compiler Collection) or any other C compiler of your choice.

# How to Compile
Copy code
gcc -o fork_example fork_example.c.
This command will compile the fork_example.c file and generate an executable named fork_example.

# How to Run
Copy code
./fork_example
This will execute the compiled program. It will fork a child process, and the child process will print "I am the child". The parent process will wait for the child to finish and then print "I am the parent".
