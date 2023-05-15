0x16. C - Simple Shell

An ALX Team project.



Description


Simple Shell is an ALX project that aimsto produce a simple UNIX command interpreter. This project is created entirely in C programming language and is intended to imitate the basic features of a typical shell, such as reading and executing user input commands.


Compilation
The shell will be compiled this way:
gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh



Testing
The shell should work like this in interactive mode:

$ ./hsh
($) /bin/ls
hsh main.c shell.c
($)
($) exit
$
But also in non-interactive mode:

$ echo "/bin/ls" | ./hsh
hsh main.c shell.c test_ls_2
$
$ cat test_ls_2
/bin/ls
/bin/ls
$
$ cat test_ls_2 | ./hsh
hsh main.c shell.c test_ls_2
hsh main.c shell.c test_ls_2
$


Resources
Read or watch:

Unix shell
Thompson shell
Ken Thompson
Everything needed to know to start coding the shell concept page


