# Mutability and Immutability

**Mutable** - Prone or liable to change.

```java

int x = 10;
```

- The value of *x* is mutable.
- The value of *10* is not mutable as it is an absolute number.


### Immutability

```java 
private final int id;
```

- The keyword *final* disables the user from the changing the value of variable *id*.
- If the variable *id* is assigned a value for a second time, it returns a compiler error.

### Java *String* objects are immutable

```java 
String a = "foo";
a = a.concat("bar");
```
- when *concat* is used a new variable is declared and the pointer of *a* points toward the new variable.
- Hence, the original variable *a* is immutable.
- **String Builder** can be used as an mutable variation of the String.
- In **String Builder**, if 2 variables with different names have the same string, both the strings point to the same object.

```java 
StringBuilder sb = new StringBuilder("foo");
sb.append("bar");

StringBuilder tb = sb;
tb.append("baz");
```

- The variable *sb* is update along with *tb* as both of them point to the same object. So the value of *sb* is "foobarbaz".


#### immutable strings can resuilt in many unnecessary copies
- E.g., Constructing a large string by concatenating many smaller things.
- Temporary 




---
Read also - 