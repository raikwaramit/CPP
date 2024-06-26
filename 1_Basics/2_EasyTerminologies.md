# Easy CPP terminologies/topics

## Output

- For printing any value on the terminal, we use cout.
  Syntax: `cout << "Hello world!" << endl;`

## New lines

- We can print new lines using `\n` and `endl`;

## Comments

- We can add comments in the programs mainly for the documentations.
- We can do it by two ways:
  - adding single line comment by adding `//` at the start.
  - enclosing the text inside `/* ---text--- */`.

## Variables

- There are mainly 5 types of primitive data type in C++.
- Integer, float, double, char, boolean

## Variable declaration

- We can declare variable using the following syntax.

```C++
dataType variableName = value;
```

```C++
dataType variableName = value, variableName2;
variableName2= value2;
```

## Indentifier

- Variable names are called identifiers.
- Unique, case-sensitive.

## Constants

- Adding `const` keyword at the start of the variable basically makes any variable a constant, non-mutable variable.
  Example: `const int newWorldCount = 1000;`

## Taking user input.

- For taking input from the user on terminal, we use cin
  Syntax: `cin >> {variable_name};`

## Datatype and its sizes in the memory

| Data Type | Size         | Description                                                                                           |
| --------- | ------------ | ----------------------------------------------------------------------------------------------------- |
| boolean   | 1 byte       | Stores true or false values                                                                           |
| char      | 1 byte       | Stores a single character/letter/number, or ASCII values                                              |
| int       | 2 or 4 bytes | Stores whole numbers, without decimals                                                                |
| float     | 4 bytes      | Stores fractional numbers, containing one or more decimals. Sufficient for storing 6-7 decimal digits |
| double    | 8 bytes      | Stores fractional numbers, containing one or more decimals. Sufficient for storing 15 decimal digits  |

## Numeric datatype

- Int float double
- Float v/s double: Precision [6/7, 15]
- scientific notation for the number(float/double)
  Example: 1.00E-3 means 0.003, it accepts both `e` and `E`.

## Boolean

- bool -> true/false or (1/0)

## Charactor

- char => Single ascii charactor is stored in the char type variable.

## String

- Array of charactor is called string.
- keyword: `string`.
- Note: it comes from the <string> library.

## Operator

- Arithmetic: +, -, \*, /, %, ++, --
- Assignment: =, +=, -=, \*=, /=, %=, &=, |=, ^|, >>= , <<=
- Comparison: <, >, <=, >=, ==, !=
- Logical: &&, ||, !
- Bitwise
