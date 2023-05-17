The printf() function sends a formatted string to the standard output (the display). This string can display formatted variables and special control characters, such as new lines ('\n'), backspaces ('\b') and tabspaces ('\t')

printf (print formatted) in C, writes out a cstring to stdout (standard output). The provided cstring may contain format specifiers( beginning with % in the cstring).

If there are format specifiers, those are replaced with their respective arguments that follow the cstring to the printf call. These format specifiers may also contain its length, precision, and other flags.

Syntax
 int printf (const char* c-string, ...);
Return Value: If the function successfully executes, it returns the total number of characters written to the standard output. If an error occurs, a negative number is returned.

Arguments: c-string is the string passed to the function. There can be additional arguments following c-string, if there exist format specifiers in the c-string, as discussed above.
