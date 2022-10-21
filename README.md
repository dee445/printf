This project encapsultes the "printf" function of the C Programming Language. The source codes below were executed thus;

0 - Writes a function that produces output according to a format.

1 - Handle the following conversion specifiers; d,i

2 - Handle the following custom conversion specifiers:

b: the unsigned int argument is converted to binary.
3 - Handle the following conversion specifiers; u,o,x,y.

4 - Uses a local buffer of 1024 chars in order to call write as little as possible.

5 - Handles the following custom conversion specifier;

S : prints the string.
Non printable characters (0 < ASCII value < 32 or >= 127) are printed this way: \x, followed by the ASCII code value in hexadecimal (upper case - always 2 characters).
6 - Handles the following conversion specifie; p.

7 - Handles the following flag characters for non-custom conversion specifiers; +, space, #.

8 - Handles the following length modifiers for non-custom conversion specifiers; l, h, Conversion specifiers to handle: d, i, u, o, x, X.

9 - Handles the field width for non-custom conversion specifiers.

10 - Handles the precision for non-custom conversion specifiers.

11 -Handles the 0 flag character for non-custom conversion specifiers.

12 - Handles the - flag character for non-custom conversion specifiers.

13 - Handles the following custom conversion specifier; r : prints the reversed string.

14 - Handles the following custom conversion specifier; R: prints the rot13'ed string.

15 - All the above options work well together.
