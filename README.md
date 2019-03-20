# printf
##### Repository for printf function, also this is the first peer proyect from Holberton School.

This directory contains the files for the __printf_ project. You will find a header file, different functions in their own files, a man page for this function and this README.md.

##### How to use:
You need to include the holberton.h header file.
Syntaxis comes on this way:

It is possible to print text directly, just typing it on the control string.
Our customized function can receive the following set of format specifiers:

Format specifier | Operation
---------------- | ---------
%c | Prints the value of a type char argument.
%c | Prints the value of an type integer argument.
%d | Prints the value of an type integer floating argument.
%s | Prints the value of an *char argument.


Filename | Description
-------- | ----------
README.md | General description of the repository
_printf.c | Our most important function.
_putchar.c | Function that allows to print a character.
holberton.h | Our header file
man_3_printf | Our man page for the _printf function
percent.c | Function that contains the flow if a '%' is found in iteration proc\
esses.
print_ch.c |Function to print a char
print_id.c |Function to print an integer given the parameters %i or %d
print_s.c |Function that allows to print a string._printf("control-string", argument-list);
