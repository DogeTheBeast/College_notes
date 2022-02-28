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

### Pre and post increment and decrement

-   Pre Increment Operator(++a): In Pre Increment Operator, the value present in the variable is incremented first and then It is used in the program.
-   Post Increment Operator(++a): In Post Increment Operator, the value present in the variable is assigned first and then It is incremented.

```c
void main()
{
	int a = 5;
	printf("%d",a++); //Output is 5
	a = 5;
	printf("%d",++a); //Output is 6
}
```

## Conditional Statements

Conditional statements are statement which execute code based on whether the given statement is true or false. Extra conditions can be added into the if statement which will be check if the first condition is not satisfied. Also, a statement (else) can be added which will execute when none of the statements in the if condition are true.

```c
void main()
{
	int a = 6;
	if(a > = 10)
	{
		printf("a is greater than 10"); // This code prints this statement only
									    // when the value of a is greater than 10
	}
	else if(a > 5)
	{
		printf("a is greater than 5"); // This code prints this statement only 
									   // when the value of a is greater than 5
	}
	else
	{
		printf("a is less than 5");
	}
}
```


## Looping

Looping is a way to repeat a set of lines of code for a limited amount of times. There are different types of loops in *C*. All loops are repeated based on a condition. When the condition is not true anymore, the loop stops and the compiler moves forward with the code. Hence, the condition needs to be updated every loop otherwise the compiler will be stuck in an infinite loop.

#### While loop

```c
void main()
{
	int a = 5;
	while(a>0)
	{
		printf("%d",a); // The output will be 54321
		a--; 			// Statement to decrease the value of a so that the while statement
						// is false after a limited amount of repetitions.
	}
}
```

The while loop repeats the block of code while the condition inside the bracket is satisfied.

#### For loop

In a for loop, a new variable is initialized which is used in testing the condition that is presented in the condition and if it true, the block of code inside the if loop is repeated.

```c
void main()
{
	for(int a = 5;a>0;a--) // The decrement operator is stated inside the for loop
	{
		printf("%d",a); // The output will be 54321
	}
}
```

## Functions




---
Read also - 