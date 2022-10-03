---
title: src/dog.hpp

---

# src/dog.hpp



## Classes

|                | Name           |
| -------------- | -------------- |
| class | **[Dog](Classes/class_dog.md)** <br>Represents a dog.  |

## Defines

|                | Name           |
| -------------- | -------------- |
|  | **[MAX_ENERGY](Files/dog_8hpp.md#define-max-energy)**  |




## Macros Documentation

### define MAX_ENERGY

```cpp
#define MAX_ENERGY 10
```


## Source code

```cpp
#ifndef DOG_HPP
#define DOG_HPP

#define MAX_ENERGY 10

class Dog {
  public:
    Dog(const char* _name);

    void bark(void);

    void run(int minutes);

    void sleep(int minutes);

  protected:
    bool checkEnergy(int energyToExpend);

  private:
    const char* name;

    int energy;
};

#endif // DOG_HPP
```


-------------------------------

Updated on 2022-10-02 at 18:55:10 +0500
