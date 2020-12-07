
# Python Programming
## Introduction:
**Python** has emerged as a first-class citizen in modern software development, infrastructure management, and data analysis. It is no longer a back-room utility language, but a major force in web application creation and systems management, and a key driver of the explosion in big data analytics and **machine intelligence**.

## Features of Python language:
* >*Free and Open Source* 
* >**Python** *is an interpreted, object-oriented, high-level programming language.*
* >*Its high-level built in data structures, combined with dynamic typing and binding.*
* >*Python has a large standard library which provides a rich set of module and functions.*

## Some disadvantages:
* >Not the fastest language.
* >Lesser libraries than C, Java, Perl.
* >Not strong on Type-binding.
* >Not easily convertible.

## Available Python distributions:
1. **CPython intallation**
   
   (which includes Python interpreter,Python IDLE and Pip.).
2. **Anaconda Python distribution**

    (which includes many packages and libraries. eg.,Numpy,Scipy IDE,Panda libraries etc.).
3. Many popular IDEs are also available eg., Spyder IDE, PytCharm IDE etc.

## Sample project 
> *The program is used to find the minimum element from a list of elements along with its index in the list.*

```python
   lst = eval(input("Enter your list:"))
   length = len(lst)
   min_ele = lst[0]
   min_index = 0
   for i in range(1,length-1):
       if lst[i] < min_ele:
           min_ele = lst[i]
           min_index = i
    print("Given list is:",lst)
    print("The minimum element of the given  list is")
    print(min_ele,"at index",min_index)
```
