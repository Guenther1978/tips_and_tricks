# Debugging with gdb

## Compiling a file with the *-g* option

gcc -g -o test test.c

## Start the debugger

gdb test

## Commands

| Command | Short form | Arguments | Description |
| --- | --- | --- | --- |
| run | r | | Start the debugger |
| step | s | | Execute next line |
| step | s | n | Execute next n lines |
| stepi | si | | Execute next assembly instruction |
| stepi | si | n | Execute next n assembly instructions |
| next | n | | Execute next line |
| next | n | n | Execute next n lines |
| nexti | ni | | Execute next assembly instruction |
| nexti | ni | n | Execute next n assembly instructions |
| list | l | n | List program since line n |
| list | l | | List whole program |
| break | b | linenumber or function | Add a breakpoint |
| delete | | n | Deletes breakpoint number n |
| continue | c | | Continue running after a breakpoint |
| info | i | register | list the content of all registers |
| info | i | breakpoints | list all breakpoints | 
| print | | variable | Prints the content of a variable |
