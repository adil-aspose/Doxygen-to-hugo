---
title: src/utility.cpp

---

# src/utility.cpp



## Functions

|                | Name           |
| -------------- | -------------- |
| int | **[square](Files/utility_8cpp.md#function-square)**(int x)<br>Squares a number.  |
| int | **[multiply](Files/utility_8cpp.md#function-multiply)**(int x, int y)<br>Multiplies two numbers.  |
| int | **[magic](Files/utility_8cpp.md#function-magic)**(int x)<br>Function for magic math.  |
| int | **[battleOfTheFiveGods](Files/utility_8cpp.md#function-battleofthefivegods)**()<br>Multiplies all the gods together.  |


## Functions Documentation

### function square

```cpp
int square(
    int x
)
```

Squares a number. 

**Parameters**: 

  * **x** The number to square.


**Return**: The square of the number. 

This function multiplies a given number by itself, which results in the square of that number.


### function multiply

```cpp
int multiply(
    int x,
    int y
)
```

Multiplies two numbers. 

**Parameters**: 

  * **x** The first operand.
  * **y** The second operand.


**Return**: The product of `x` and `y`. 

This function multiplies a number times another number and returns the result of those two numbers multiplied together. The result is the product of the two numbers, and that is the value that is returned by this function.


### function magic

```cpp
int magic(
    int x
)
```

Function for magic math. 

**Parameters**: 

  * **x** The number on which to perfom magic.


**Return**: The magic product of the number. 

This function multiplies a number by the magic number.


### function battleOfTheFiveGods

```cpp
int battleOfTheFiveGods()
```

Multiplies all the gods together. 

**Return**: The product of the five numbers. 

This function just multiplies the five god constants together.




## Source code

```cpp
#include "utility.hpp"

int square(int x) {
    return x * x;
}

int multiply(int x, int y) {
    return x * y;
}

int magic(int x) {
    return MAGIC_NUMBER * x;
}

int battleOfTheFiveGods() {
    return MEW2KING * ARMADA * HUNGRYBOX * MANGO * PPMD;
}
```


-------------------------------

Updated on 2022-10-02 at 18:55:10 +0500
