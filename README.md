# Cplus-code
# progress of me learning C++


# Basics
1) Function: A function is a piece of code that contains a series of instructions to        complete a task

The main function is the main function, it is an entry point.
denoted as    
int main()     <----- Function header
{
    All commands go between function body(the part between {})
    Statement1();
    Statement2();
    [We must add ; to the end of each statement]
}

some functions require inputs, they go into ()
eg. int main(age)


2) Libraries: These contain premade functions

we can include the library using include directive

"#include <Library name>"

to call a function from the library we use 
    Function();


3) Compiler: The compiler plays the role of translator converting C++ to binary
the compiler is an important part because they generate error messages/syntax errors in our code that allows us to know about them

A compiler can detect code errors
human errors are those which are made by us meaning the code is technically correct but gives an output not the same as ours

4) Comments: allow to organize and add messages in the code using //(single line comments) and /*(Multi line comments)*/