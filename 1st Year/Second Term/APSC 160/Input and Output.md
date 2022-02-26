# Input and Output

## printf and its variations

*printf* is a function used to output text. When using *printf*, the variable that is going to be printed is represented by a placeholder. For example

```c 
int a = 10;
printf("%o", a);
```

The term inside the double quotes is the placeholder and it replaces its value with the variable present after the comma. The *%o* gives the type of output it presents. This can be changed to present the variable as different datatypes.

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

Pay attention to the number of spaces before the first digit of the output. The decimal is also taken into account when the field width is calculated.



## scanf and its variations






---
Read also - 