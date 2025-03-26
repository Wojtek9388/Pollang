--------------- PolLang ---------------
A weird language

Capitals dont matter

can be run through interpreters or compiled

it was made mostly for fun

--------------- Credits ---------------

Wojtek

---------------------------------------

------------- File Stuffs -------------

Main Filetype
- .plm

Header Filetype
- .plh

---------- Runtime Arguments ----------

BOOL gui
- Not required to run
- Allows use of GUI functions

BOOL guiconsole
- Not required to run
- Shows a console even when making a GUI project for easy debugging

BOOL customargs
- Not required to run
- allows users to pass custom arguments to the program

-------------- DataTypes --------------

int         1
bool        true false
string      ""
vector      ()
- A vector NEEDS to have a data type so you cant have a two different types in the same vector
- Example: vector<DATATYPE> NAME
dictionary  []
block scope {}

------------ Misc Features ------------

//  comment
;   endline
Null

-------------- Functions --------------

#include "FILENAME"

#define ()
- Allows you to define pi a radian or degree

print(ANY)
- Prints text to the console

return(DATATYPE OF FUNCTION ITS CALLED FROM)
- returns data to the point its called at

warn(STRING)
- used to warn if a function is deprecated or if a function isnt fully working right it will log it

error(STRING OR INT)
- used for stoping the program in case of a error that cant be handled without breaking the program

RETURNTYPE func or function NAME
- Function definition

class NAME()
- Class definition

DATATYPE NAME
- Variable definition

http(INT METHOD)
- 0 Post
- 1 Get
- 2 Put
- 3 Delete

// gui functions will be added soon

------------ Func Examples ------------

ANY main(RUNTIME ARGS)
{
    int Number;
    Number = 0;

    string Letters = "Hello, World!";

    return FUNCTIONTYPE;
}

class Example()
{
    func Hello(int Count)
    {
        for (i in range(0, Count))
        {
            print("Hello, World!");
        }
        return 0;
    }

    int A = 1325;
}

// to get functions you do
Example.Hello(7);\

// you can do the same with variables
print(Example.A);
