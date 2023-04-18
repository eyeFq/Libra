<H1> Libra Syntax & More </H1>


## Introduction
Libra is a cool project idea I had on this date 11/11/22. I made it because I want to learn more about how languages do cool shit, also because I might be able to just use it in some obscure project at one point, so that'll be fun, also who else can say I made my own programming language ~(I know a few people can but now I will be able to aswell).~ 
I may also have a compiler and interpreter for it, as I think this might help people wanting to tweak their scripts or program quickly without having to recompile everytime but the compiled version will obviously be faster.
The file extension will probably be .libsrc and for any header files .brali (I may change this because I though of these in like 5 min)

### Before using Libra:
Currently there is **no** documentation, and this is hardly a proper idea and is still being worked on, also be aware I'm also using this to help me learn other languages too :)


## Installation
(I have no clue what I'm doing so I'll do this later )

## Example Code:
```cpp
// Single Line Comment

// {Some code here}; // This is also a valid comment

/*
    Multi-line comment
*/

// All code has a main function
fn Main() {

    int i = 5;
    string a = "a string";

    i += 1;
    i -= 1;
    i /= 1;
    i *= 1;

    while( i < 15) {
        i *= 3;
    }

    if (a == "a string") {
        // Print function
        output(a);
        output("Variable Name: \ta");
        output("Variable Value: \t{a}");
        // Output: {VarName} is {VarVal}
    }
}

// Declare a new function with "fn", then the function name, and the input variables.
// The input variables need a type
// Functions don't need input variables
// The functions return type is defined with "->" then the type
// Not all functions need to return anything
fn ExampleFunction(int input_int_1, int input_int_2) -> int {
    int sum = input_int_1 + input_int_2;
    // Print function
    // Output: "the sum is: " + {sum}

    return(0);
}

fn Example2() -> string {
    string msg = "hello";

    return(msg);
}

fn Compare_File_Content(string: FILE_DIR) {
    // File Access func needs the file directory and the permission needed (read - 0, write & read - 2, execute - 3)
    string Content_Arr[] = file_access_func(FILE_DIR, 0);
    if (Content_Arr[1] =~ m!^/[hH]ello [wW]orld\! $!) {
        output("");
    }
}

fn GlobalFunction_Example() {
    global string access_me = "https://youtu.be/dwDns8x3Jb4";
    global char glob_char = 'e';
}
```