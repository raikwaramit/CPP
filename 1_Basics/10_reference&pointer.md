# Reference and pointers

## Reference

It just create a another variable which basically is referencing to the same variable.

```C++
string food = "Pizza";  // food variable
string &meal = food;    // reference to food
```

In above snippets, we meal is pointing to food. so if we try to print the meal `Pizza` will be print.

& = This is called reference operator, which is oftenly used for getting the memory address of the variable.
Returns a hex value like 0x6dfed4.

## Pointer

Pointer is basically a variable which is designed to keep the memory address of the specified datatype.

```c++
string* mystring; // Preferred
string *mystring;
string * mystring;
```

When we want the value of the pointer address.
-> We use dereferencing operator like `cout << *ptr << "\n";`

So we can also manipulate the value of the pointer using the dereferencing operator.

```c++
// Change the value of the pointer
*ptr = "Hamburger";
```
