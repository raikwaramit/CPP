# About CPP

C++ was developed by Bjarne Stroustrup. It has 4 major updates in the 2011, 2014, 2017 and 2020.

## Difference between C and C++

Main difference is C++ supports Classes and object concept whereas C does not.

## Understanding the basic code snippet.
```C++
#include <iostream>
using namespace std;

int main() {
  cout << "Hello World!";
  return 0;
}
```
A C++ program is basically a block of code which have main function which is executed. When we run the code compiler search for the main function which generally return 0 telling compiler that main function is successfully executed. 

Breaking down each line.
- First line is basically including or importing the functionality of `cout <<` from iostream which is basically a header file.
- Second line, is basically telling the compiler about the namespaces that we are using this function or variable from this library. For example: if we remove the namespace from here then we have to write `std::cout<< "";`.
- Third line is where main funtion start and its telling this function is going to return a integer value at last.

