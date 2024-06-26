# Structure

Structure is basically a custom type where we put together related variables.

```c++
struct {             // Structure declaration
  int myNum;         // Member (int variable)
  string myString;   // Member (string variable)
} myStructure;       // Structure variable
```

## ways to define structure

First way

```c++
struct {
    string carName;
    int carId;
} structureInstance1, ....;
```

Second way | Named structure

```c++
struct MyType{
    string carName;
    int carId;
};

MyType car1;
car1.carName = "Car";
car1.carId = 1;
```
