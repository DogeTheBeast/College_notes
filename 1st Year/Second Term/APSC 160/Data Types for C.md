# Data Types for C

| Name     | Type      | Format | Notes                                                                    |
| -------- | --------- | ------ | ------------------------------------------------------------------------ |
| *int*    | Numeric   |        | Stores only integers (No Decimals)                                       |
| *float*  | Numeric   |        | Can include decimals                                                     |
| *double* | Numeric   |        | Double the amount of precision compared to float (double decimal places) |
| *char*   | Character |        | Stores a single character                                                |
| *_Bool*  | Boolean   |        | Stores only true or false values (1 or 0)                                |

## Typecasting in *C*

Typecasting is converting one datatype into another. This is generally used in division as division can lead to a float point value from an input of 2 integers. Consider the following example,

```c
void main()
{	
	int a = 10;
	int b = 15;
	double c;
	c = a/b;
	printf("%lf",c); // The output of this program in 
}








---
Read also - 