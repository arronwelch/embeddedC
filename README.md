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
    - Statements and Blocks:
    ```
       An expression such as **x = 0** or **i++** or **printf(...)** becomes a _statement_ when it is 
    followed by a semicolon, as in
       > x =0;
       > i++;
       > printf(...);
    In C, the semicolon is a statement terminator, rather than a separator as it is in languages like
    Pascal.  
    
    Braces *{* and *}* are used to group declarations and statements together into a _compound statement_,
    or _block_, so that they are syntactically equivalent to a single statement.The braces that surround
    the statements of a function are one obvious example; braces around multiple statements after an _if_,
    _else_,_while_,or _for_ are another.(Variables can be declared inside _any_ block;we will talk about
    this in Chapter 4.) There is no semicolon after the right brace that ends a block.
    ```
    - left value:  
    ```
    In C,the concept was renamed as "locator value"
    "l-value" refers to memory location which identifies an object.l-value may appear as either left
    hand or right hand side of an assignment operater(=).l-value offten represents as identifier.
    ```
    - right value:  
    ```
    "r-value" refers to data value that is stored at some address in memory. A r-value is an expression
    that can't have a value assigned to it which r-value can appear on right but not on left hand side 
    of an assignment operator(=).
    Note: The unary &(address-of) operator requires an lvalue as its operand.That is,&n is a valid 
    expression only if n is an lvalue.Thus,an expression such as &12 is an error.Again,12 does not refer
    to an object, so it's not addressable.
    ```
    - Objects and Lvalues:
    ```
    An _Object_ is a named region of storage;an _lvalue_ is an expression referring to an object.
    An obvious example of an lvalue expression is an identifier with suitable type and storage class.
    ```
    - side effect:  
    ```

    ```
    - undefined behaviour:  
    ```

    ```
