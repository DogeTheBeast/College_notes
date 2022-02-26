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
	int a = 15;
	int b = 10;
	double c;
	c = a/b;
	printf("%lf",c); // The output of this program in "1.000000".
}
```

This happens because both the numbers used in division are integers. Therefore, the compiler tries to return a value in the form of an integer, truncating the values after the decimal. To fix this, we use a special declaration which tells the compiler that the return of the di







---
Read also - 