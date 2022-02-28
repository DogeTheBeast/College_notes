# Input and Output

## printf and its variations

*printf* is a function used to output text. When using *printf*, the variable that is going to be printed is represented by a placeholder. For example

```c 
int a = 10;
printf("%o", a);
```

The term inside the double quotes is the placeholder and it replaces its value with the variable present after the comma. The *%o* gives the type of output it presents. This can be changed to present the variable as different datatypes.

This can be done for multiple variables as well but the order of the variables has to be the same as the format specifiers.

```c 
int a = 10;
float b = 11.1;
printf("%o %lf", a, b); // The output will be "10 11.1"
```

### The Variations

These are the arguments that can go inside the double quotes in the printf statement.

| Argument | Datatype                           |
| -------- | ---------------------------------- |
| %c       | Character                          |
| %d       | Integer                            |
| %e       | Scientific Notation                |
| %f       | Float                              |
| %g       | Chooses the best between %e and %f |
| %o       | Octal integer                      |
| %s       | String                             |
| %x       | Hexadecimal integer without 0x     |
| %#x      | Hexadecimal integer with 0x        |
| \n       | New line                           |

### Special Cases of octal and hexadecimal integers

To assign a octal integer to a variable and clarify that it is in the base of 8, we place a 0 before the value of the integer. For example,

```c
int a = 067;
int b = 67;
```
Integers a and b are different because a has a 0 before the 67. This means that a is actually 55 in base 10.

Something similar is valid for Hexadecimal integers as well. Instead of a 0, we place a 0x in front of the hexadecimal.
```c
int a = 0xEEFF0D;
```

### Decimal places and field width

The decimal places for a given output can be specified by doing the following,

```c
void main()
{
	float num = 1.123456;
	printf("%.2lf",num); // The output of this will be 1.12 (up to 2 decimal places)
}
```

Something similar can be used to define the number of spaces a number can take when printed out.

```c
void main()
{
	float num = 1.123456;
	printf("%6.2lf",num); // The output of this will be "  1.12"
}
```

Pay attention to the number of spaces before the first digit of the output. The decimal is also taken into account when the field width is measured. This is true for any other symbol as well such as a negative sign (-).

If a negative sign is placed before the format specifier, then the number of empty spaces added to the number will be to the right. So,
```c
void main()
{
	float num = 1.123456;
	printf("%-6.2lf",num); // The output of this will be "1.12  "
}
```


## scanf


scanf is used to ask the user for an input through the console. The input is then assigned to a variable and the variable can be used inside the program. scanf takes in a format specifier and a variable. The format specifier tells scanf the type of input that is expected from the user (in the code below, it is integer) and then assigns it to input. The & sign before input tells the compiler to look for the variable called input inside the memory.

```c
void main()
{
	int input;
	printf("Enter any integer value");
	scanf("%d", &input); // This program asks the user for an input and assigns that value 
						 // to the variable called input.
}
```



## Inputting a file


The basic steps to input a file into *C* are as follows:-

1. Create a variable of type "FILE*".
2. Open the file using "fopen" function and assign the file to the variable.
3. Check to make sure the file was successfully opened by checking to see if the variable == NULL. If it does, then an error has occurred in reading the file.
4. Use the fprintf or fscanf functions to write/read from the file. Usually these function calls are placed in a loop. In the case of reading data, usually, the data is read in and placed in an array, but sometimes we process the data "on the fly" (i.e., we do not store the data, we process it and create a result directly before reading any more data.

A basic sample of opening a file is presented below (with the input file called "data.txt").

```c
void main()
{
	FILE* file;
	file = fopen("data.txt","r");
	
	if(file != NULL)
	{
		printf()
	}
}



---
Read also - 