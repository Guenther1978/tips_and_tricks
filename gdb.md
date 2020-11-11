# Debugging with gdb

## Compiling a file with the *-g* option

gcc -g -o test test.c

## Start the debugger

gdb test

## Commands

| Command | Short form | Arguments | Description |
| --- | --- | --- | --- |
| break | b | linenumber or function | Add a breakpoint |
| delete | | n | Deletes breakpoint number n |
| info | i | register | list the content of all registers |
| | | breakpoints | list all breakpoints | 
| print | | variable | Prints the content of a variable |
