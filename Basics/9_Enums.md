# Enums (Enumeration)

A group of constants which are related to each other.

```c++
enum Level {
LOW,
MEDIUM,
HIGH
};
```

Assigning different values.

```c++
enum Level {
LOW = 10,
MEDIUM = 30,
HIGH = 50
};
enum Level firstLevelInstance = LOW;
```

Using enum in a switch statement is pretty helpful, in which if all the cases are covered we don't need to add default case.
Note: Enum value are the case value.
