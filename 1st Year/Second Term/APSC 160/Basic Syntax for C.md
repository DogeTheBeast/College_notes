# Basic Syntax for C

## Comments
Comments in *C* are surrounded by either of the two ways presented below.
```c
/*	This 
*	is
*	a 
*	Multi
*	Line
*	Comment
*/

// This is a single line comment.
```

## Basic *C* libraries

Below is a list of basic *C* libraries that are used in general programs along with the functionality they offer.

| Library  | Functionality                                            |
| -------- | -------------------------------------------------------- |
| stdio.h  | Standard input and output library                        |
| stdlib.h | Better memory allocation and other general functionality |

To include a library in *C*,

```c
// This adds a library to the program
#include <stdio.h>
```


## Main function

The main function contains what the program will actually perform and it is the first function that will be called when the program is executed. The return type is integer by default and it returns a 0 (it is not necessary) with the program ends but it can be changed to a different data type such as void ([[Data Types for C]]).

```c
int main (void){

	// Your code goes here
	
	return 0;
	
}
```


## Define

Define is a macro definition that is not a variable. That means it has an absolute value which can't be changed while the program runs and it, practically, only substitutes the value of the define object into the code.

```c
#define Name "Ratiq"
#define Size 15


---
Read also - 