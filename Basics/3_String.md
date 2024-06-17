# String

A string variable contains a collection of characters surrounded by double quotes:

```c++
string greeting = "Hello";
```

## String class property

| Function   | Description                                                                   |
| ---------- | ----------------------------------------------------------------------------- |
| at()       | Returns an indexed character from a string                                    |
| length()   | Returns the length of a string                                                |
| size()     | Alias of length(). Returns the length of a string                             |
| max_size() | Returns the maximum length of a string                                        |
| empty()    | Checks wheter a string is empty or not                                        |
| append()   | Appends a string (or a part of a string) to another string                    |
| substr()   | Returns a part of a string from a start index (position) and length           |
| find()     | Returns the index (position) of the first occurrence of a string or character |
| replace()  | Replaces a part of a string with another string                               |
| insert()   | Inserts a string at a specified index (position)                              |
| erase()    | Removes characters from a string                                              |
| compare()  | Compares two strings                                                          |

## Numbers and Strings

- `+` operator is used for both addition and concatenation.

## string length

- length() or size() both can be used to get the string length.

## Accessing the character of the string

- [ index ] or at(index).
  Note: We should keep this in mind that index is an integer always greater than String length.

- We can access the string character or assign a new value using the [], at().

## Escape sequences

- \t - tab
- \n - new line
- \' - single quote
- \" - double quote
- \\ - backslash

## Getting user input from a user

cin>> variable_name;

## Getting a whole line as input

Generally ` ` (space) and newline are considered as input stream breaker, so when we use getLine(cin, variable_name);
` ` space is not treated as stream breaker when we use getline.

## C style string.

As we know, string is just array of the characters of finite length.
So we can just write `char a[]= "Amit";` to create a string.

- We have whole library of the Cstring which provides the legacy function and property of the strings.
