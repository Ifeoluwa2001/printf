**C-printf collaboration task**
This program is a custom implementation of the standard C library function printf. It provides a set of conversion specifiers, flag characters, and length modifiers to format and output text to the console or other output streams.

The supported conversion specifiers are as follows:

**%c**: Prints a single character.
**%s**: Prints a null-terminated string.
**%d, %i, %u, %o, %x, %X**: Prints a signed/unsigned integer in decimal, octal, or hexadecimal format.
**%p**: Prints a pointer address.
**%S**: Prints a string with non-printable characters represented as \xXX, where XX is the ASCII code value in hexadecimal (always in uppercase).

The supported flag characters are:

**0**: Left-pads the output with zeros instead of spaces.
**#**: Left-justifies the output within the given field width.
**+**: Always prints the sign of a signed number (+ or -).
**space**: Prints a space before a positive number (overrides the + flag).

The supported length modifiers are:

**h**: Short (for integers).
**l**: Long (for integers).
Additionally, the program introduces two custom conversion specifiers:

**%r**: Prints the reversed string.
**%R**: Prints the rot13'ed string.
To avoid excessive calls to the write function, the program uses a maximum buffer size of 1024 characters for the field width.

AUTHORS
This project is a collaboration between:
# **Ifeoluwa A. Ajiboye**
# **Chinaza Nedolisa**
