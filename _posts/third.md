---
layout: single
title:  "Function vs Methods in Python"
categories: coding
tags: [DSA in Python]
toc : true
---

Function vs Method in Python

A function does not belong to a class and it is implemented outside of a class. ex) print()
A method belongs to a class and can be only implemented with objects inside of a class ex) upper()

```python
class Weight():
    weight = 100

    # Defining a method
    def to_pounds(self):
        return 2.205 * self.weight

# Defining a function
def to_pounds(kilos):
    return 2.205 * kilos

# Calling a method on an object.
w = Weight()
pounds = w.to_pounds()

# Calling a function on an object
kilos = 100
pounds = to_pounds(kilos)
```
