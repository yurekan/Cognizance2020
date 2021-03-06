
# Python Programming

## Introduction:

![Python](https://hub.packtpub.com/wp-content/uploads/2018/03/Should-you-move-to-Python-3_image.png)

**Python** has emerged as a first-class citizen in modern software development, infrastructure management, and data analysis. It is no longer a back-room utility language, but a major force in web application creation and systems management, and a key driver of the explosion in big data analytics and **machine intelligence**.

## Features of Python language:

![PythonLanguage](https://www.python.org/static/opengraph-icon-200x200.png)

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

![Interpreter](https://data-flair.training/blogs/wp-content/uploads/sites/2/2018/07/Python-Interpreter-01.jpg)

   (which includes Python interpreter,Python IDLE and Pip.).

2. **Anaconda Python distribution**

  ![anaconda](https://3qeqpr26caki16dnhd19sv6by6v-wpengine.netdna-ssl.com/wp-content/uploads/2017/03/How-to-Setup-a-Python-Environment-for-Machine-Learning-and-Deep-Learning-with-Anaconda-1024x512.png)


 (which includes many packages and libraries. eg.,Numpy,Scipy IDE,Panda libraries etc.).

3. Many popular IDEs are also available eg., Spyder IDE, PytCharm IDE etc.

![Pandas](https://upload.wikimedia.org/wikipedia/commons/thumb/e/ed/Pandas_logo.svg/1200px-Pandas_logo.svg.png)

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
    print("The minimum element of the given  list is:")
    print(min_ele,"at index",min_index)

```
### Explaination of the project:
* **Line1** - Asking for the user to enter a  list.
* **Line2** - Initialzing length of list       to variable "Length".
* **Line3** - Initialzing first element of the list as minimum element.
* **Line4** - Initialzing index of minimum element.
* **Line5** - Loopin the variable "i" inside the list.
* **Line6** - condition check, whether the element of list is less than the minimum element.
* **Line7** - If the condition is TRUE ,then it modifies the minimum element.
* **Line8** - If the condition is TRUE ,then it modifies the min_index to the index of minimum element.
* **Line9** - Prints the given list.
* **Line10** - Prints the minimum element.
* **line11** - Prints the index of the minimum element.

### Outout of the project :
Enter your list: [2,3,4,-2,6,-7]


Given list is: [2,3,4,-2,6,-7]


The minimum element of the given  list is: -7 at index 5

## Links Refered
* [Link1](https://www.infoworld.com/article/3204016/what-is-python-powerful-intuitive-programming.html "InfoWorld")


* [Link2](https://www.python.org/doc/essays/blurb/ "Python official")

* [Link3](https://www.geeksforgeeks.org/python-features/ "GeeksforGeeks")


## Books Refered
* *Computer Science With Python by SUMITA ARORA*
* *Saraswati Computer Science* 

