---
title: Dog
summary: Represents a dog. 

---

# Dog



Represents a dog.  [More...](#detailed-description)


`#include <dog.hpp>`

## Public Functions

|                | Name           |
| -------------- | -------------- |
| | **[Dog](Classes/class_dog.md#function-dog)**(const char * _name)<br>Creates a new [Dog](Classes/class_dog.md).  |
| void | **[bark](Classes/class_dog.md#function-bark)**(void )<br>Causes the dog to bark.  |
| void | **[run](Classes/class_dog.md#function-run)**(int minutes)<br>Causes the dog to run.  |
| void | **[sleep](Classes/class_dog.md#function-sleep)**(int minutes)<br>Causes the dog to sleep.  |

## Protected Functions

|                | Name           |
| -------------- | -------------- |
| bool | **[checkEnergy](Classes/class_dog.md#function-checkenergy)**(int energyToExpend)<br>Checks the dog's energy.  |

## Detailed Description

```cpp
class Dog;
```

Represents a dog. 

This class keeps track of the dog's energy level, and performs actions for the dog based on how much energy it has. Sleeping regains energy for the dog, while barking and running use energy up. 

## Public Functions Documentation

### function Dog

```cpp
Dog(
    const char * _name
)
```

Creates a new [Dog](Classes/class_dog.md). 

**Parameters**: 

  * **_name** The dog's name. 


Creates a new [Dog](Classes/class_dog.md) named `_name` with half of its maximum energy.


### function bark

```cpp
void bark(
    void 
)
```

Causes the dog to bark. 

Causes the dog to bark if it has enough energy to do so. Barking costs 1 energy to do. If the dog does not have enough energy, then the bark fails. 


### function run

```cpp
void run(
    int minutes
)
```

Causes the dog to run. 

**Parameters**: 

  * **minutes** Number of minutes for the dog to run. 


Causes the dog to run for an amount of time if it has enough energy to run for that long. If the dog does not have enough energy, then the run fails. If the dog cannot complete the full run, no running takes place and no energy is expended. Running costs 3 energy per minute.


### function sleep

```cpp
void sleep(
    int minutes
)
```

Causes the dog to sleep. 

**Parameters**: 

  * **minutes** Number of minutes for the dog to sleep. 


Sleeping replenishes the dog's energy. The dog regains an amount of energy equal to twice the number of minutes slept. The dog will always sleep, regardless of how much energy it has remaining.


## Protected Functions Documentation

### function checkEnergy

```cpp
bool checkEnergy(
    int energyToExpend
)
```

Checks the dog's energy. 

**Parameters**: 

  * **energyToExpend** An amount of energy to check.


**Return**: True if the dog has enough energy, and false otherwise. 

Compares an amount of energy with the dog's current available energy. This function can be used to determine if the dog is able to take an action that costs energy.


-------------------------------

Updated on 2022-10-02 at 18:55:10 +0500