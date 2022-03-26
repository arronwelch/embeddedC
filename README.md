# embeddedC
- C language base review:
    - identifiers:
    ```
    An identifier is a sequence of letters and digits.
    The first character must be a letter;
        the underscore _ counts as a letter.
        Upper and lower case letters are different.
        Identifiers may have any length..
    ```
    - Keywords:
    ```
        auto     double   int      struct
        break    else     long     switch
        case     enum     register typedef
        char     extern   return   union
        const    float    short    unsigned
        continue for      signed   void
        default  goto     sizeof   volatile
        do       if       static   while
        The keywords const,signed,and volatile are new with the ANSI standard;
        enum and void are new since the first edition,but in common use;
        entry, formerly reserved but never used, is no longer reserved.
    ```
    - predefined names:
    ```
        __LINE__ A decimal constant containing the current source line number.
        __FILE__ A string literal containing the name of the file being compiled.
        __DATE__ A string literal containing the date of compilation, in the form "Mmmm dd yyyy"
        __TIME__ A string literal containing the time of compilation, int the form "hh:mm:ss"
       __STDC__ The constant 1.It is intended that this identifier be defined to be 1 only in standard-
             conforming implementations.
    ```
    - syntax error:
    ```
       - Spelling mistakes
       - Missing out quotes
       - Missing out brackets
       - Using upper case characters in key words e.g IF instead of if
       - Missing out a colon or semicolon at end of a statement
       - Using tokens in the wrong order
    ```
    - logical error:
    ```
       A logical error is a 'bug' or mistake in a program's source code that
       results in incorrect or unexpected behaviour.It is a type of runtime error that
       may simply produce the wrong output or may cause a program to crash while running
    ```
    - expressions:
    ```
       In C, any assignment,such as
              c = getchar();
       is an expression and has a value, which is the value of the left hand side after the assigment.
