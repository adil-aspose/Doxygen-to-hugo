---
title: src/utility.hpp

---

# src/utility.hpp



## Functions

|                | Name           |
| -------------- | -------------- |
| int | **[square](Files/utility_8hpp.md#function-square)**(int x)<br>Squares a number.  |
| int | **[multiply](Files/utility_8hpp.md#function-multiply)**(int x, int y)<br>Multiplies two numbers.  |
| int | **[magic](Files/utility_8hpp.md#function-magic)**(int x)<br>Function for magic math.  |
| int | **[battleOfTheFiveGods](Files/utility_8hpp.md#function-battleofthefivegods)**()<br>Multiplies all the gods together.  |

## Defines

|                | Name           |
| -------------- | -------------- |
|  | **[MEW2KING](Files/utility_8hpp.md#define-mew2king)** <br>Five Gods constants.  |
|  | **[ARMADA](Files/utility_8hpp.md#define-armada)**  |
|  | **[HUNGRYBOX](Files/utility_8hpp.md#define-hungrybox)**  |
|  | **[MANGO](Files/utility_8hpp.md#define-mango)**  |
|  | **[PPMD](Files/utility_8hpp.md#define-ppmd)**  |
|  | **[MAGIC_NUMBER](Files/utility_8hpp.md#define-magic-number)** <br>Magic number for magical computation.  |


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




## Macros Documentation

### define MEW2KING

```cpp
#define MEW2KING 1
```

Five Gods constants. 

These five constants represent the five gods. 


### define ARMADA

```cpp
#define ARMADA 2
```


### define HUNGRYBOX

```cpp
#define HUNGRYBOX 3
```


### define MANGO

```cpp
#define MANGO 4
```


### define PPMD

```cpp
#define PPMD 5
```


### define MAGIC_NUMBER

```cpp
#define MAGIC_NUMBER 1337
```

Magic number for magical computation. 

This number is selected to be the most elite number there is. No other numbers are more elite than this number. 


## Source code

```cpp
#ifndef UTILITY_H
#define UTILITY_H

#define MAGIC_NUMBER 1337

#define MEW2KING  1
#define ARMADA    2
#define HUNGRYBOX 3
#define MANGO     4
#define PPMD      5
int square(int x);

int multiply(int x, int y);

int magic(int x);

int battleOfTheFiveGods();

#endif // UTILITY_H
```


-------------------------------

Updated on 2022-10-02 at 18:55:10 +0500
