# Exceptions in C++

Try catch block is basically for avoiding stopping program execution when any error occurs.

```cpp
try{
// Code that can cause error.

// 'throw' keyword is generally use to throw errors.

}
catch () {
// if error occurs then this code block will be executed.
}

```

using `catch(...)` : This can catch any types of error

other wise it is necessary to use the type and error variable in the catch ().
