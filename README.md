# Bourne-Shell-Again-for-dummies
My biggest personal and university project so far. Written entirely in C.

The purpose of this project is to implement a small(micro) shell in order to get familiar 
with the basic POSIX system calls for process management. It's pretty simple
and basic, it lacks a lot of features, for example, it's required there is no blanks between 
the '>' character and the name of the file to redirect the standard output of a command, 
also it doesn't handle filename expansion, escape sequences, strings, process groups, 
foreground/background processes and many other things.

It can run one or more commands, redirect the standard input and output,
print the command history and it has an unique built-in command, cd 
(change directory).

$ make

$ ./ubash

For the readline library: $ sudo apt-get install libreadline-dev

Be aware that Prof. Lagorio is aware of this code. DON'T EVEN TRY.
