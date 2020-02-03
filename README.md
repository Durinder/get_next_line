get_next_line returns a line read from a file descriptor.
A “line” is a succession of characters that end with ’\n’ (ascii code 0x0a) or with End Of File (EOF).

get_next_line takes two parameters. The first parameter is the file descriptor that will be used to read.
The second parameter is the address of a pointer to a character that will be used
to save the line read from the file descriptor.

get_next_line returns either 1, 0 or -1 depending on whether a line has been read,
when the reading has been completed, or if an error has happened respectively.
