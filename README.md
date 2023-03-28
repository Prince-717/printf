THIS PROJECT SEEKS TO WRITE A FUNCTION "_PRINTF" THAT WORKS LIKE THE "PRINTF" FUNCTION IN C.

The code defines a custom printf function named "_printf" that takes in a variable number of arguments, with the first argument being a string format. The function iterates through the format string, parsing it for format specifiers that start with a '%'.

If a format specifier is found, the function determines the formatting options (such as flags, width, precision, and length modifier) and extracts the corresponding argument from the variable argument list. The function then prints the formatted argument to the output buffer, which is flushed to stdout when it is full or at the end of the format string.

If a non-format specifier character is encountered, it is added to the output buffer until the buffer is full or the end of the format string is reached. If the format string is NULL, the function returns -1 to indicate an error.

The function returns the total number of characters printed to stdout.
