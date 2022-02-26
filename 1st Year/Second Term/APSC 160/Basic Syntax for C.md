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

void main()
{	
	int Double_size;
	Double_size = 2*Size; //Here size is substituted by the value of 15.
	printf("%s", Name); //This prints out Ratiq
	// This is fine as C sees that Name is defined and substitutes the value of Name into %s.
}
```

## Increments and Decrements

There are 6 possible ways to affect a number (increment or decrement). They are
```c
a++;	//increases the value of a by 1
a+=b;	//increases the value of a by b
a--;	//decreases the value of a by 1
a-=b;	//decreases the value of a by b
a*=b;	//multiplies a by b every iteration
a/=b;	//divides a by b every iteration
```

### Preprocessing and post processing

Preprocessing refers to when the increment or decrement is performed 


These Operators are known as Increment operators. Increment Operators has two types:

-   Pre Increment Operator(++a): In Pre Increment Operator, the value present in the variable is incremented first and then It is used in the program.
-   Post Increment Operator(++a): In Post Increment Operator, the value present in the variable is assigned first and then It is incremented.

Below is the code for the explanation of the increment operators:

-   main() { 

-    int a = 21; 

-    int c ; 

-    // Value of a will not be increased before assignment. 

-    c = a++;  

-    cout << "Line 1 - Value of a++ is :" << c << endl ; 

-    // After expression value of a is increased 

-    cout << "Line 2 - Value of a is :" << a << endl ;  

-    // Value of a will be increased before assignment. 

-    c = ++a;  

-    cout << "Line 3 - Value of ++a is  :" << c << endl ; 

-    return 0; 

-   } 

-   Output: 

-   Value of a++ is :21 

-   Value of a is :22 

-   Value of ++a is  :23
---
Read also - 