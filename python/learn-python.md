# Learn Python: Basics

The requirements for machine learning are that you have a good grasp of basic Computer Science concepts and their implementation \(or usage\) in Python.

* _Strings, numbers, and variables_
* _Statements, operators, and expressions_
* _Lists, tuples, and dictionaries_
* _Conditions, loops_
* _Procedures, objects, modules, and libraries_
* _Troubleshooting and debugging_
* _Research & Documentation_
* _Problem solving_
* _Algorithms and data structures_

_**For our requirements, we are going to assume Python 3 usage in order to be prepared to work with iPython \(and Jupyter\) notebooks for future projects. **_[_**Read this page**_](https://wiki.python.org/moin/Python2orPython3)_** or **_[_**this article from Wesley Chun \(Google\)**_](https://www.quora.com/As-someone-interested-in-learning-Python-should-I-start-with-2-x-or-go-straight-to-3-x/answer/Wesley-Chun?srid=hFhk&share=1)_** for why Python 3 is the way to go when starting from scratch like we are, and where you can learn about the differences \(and migration path\) from Python 2.**_

These are notes from the online [Learn Python](http://learnpython.org/) Tutorials. In this section we'll cover the **Basics** portion of those tutorials consisting of the following parts.

* [Hello, World!](http://learnpython.org/en/Hello%2C_World!)
* [Variables and Types](http://learnpython.org/en/Variables_and_Types)
* [Lists](http://learnpython.org/en/Lists)
* [Basic Operators](http://learnpython.org/en/Basic_Operators)
* [String Formatting](http://learnpython.org/en/String_Formatting)
* [Basic String Operations](http://learnpython.org/en/Basic_String_Operations)
* [Conditions](http://learnpython.org/en/Conditions)
* [Loops](http://learnpython.org/en/Loops)
* [Functions](http://learnpython.org/en/Functions)
* [Classes and Objects](http://learnpython.org/en/Classes_and_Objects)
* [Dictionaries](http://learnpython.org/en/Dictionaries)
* [Modules and Packages](http://learnpython.org/en/Modules_and_Packages)

## [Hello World](http://learnpython.org/en/Hello%2C_World!)

Concepts introduced in this section

* **Print Statement: **print statement in Python3 is a function:  `print("Hello world!"`
* **Comments**: use \# for single-line comments
* **Indentation**: Python uses indentation for blocks \(not braces\). Use tabs or spaces to indent.

_Things to try:_

1. _Remove indentation_
2. Add comments on 1 line, many lines, end of line
3. Print without parentheses

## [Variables And Types](http://learnpython.org/en/Variables_and_Types)

* **Python is dynamically typed \(not statically typed like Java\)**. You don't need to declare variables \(or their types\) before using them - rather the type of the variable is decided by run-time value assigned to it.
* **Python is object-oriented.** Every variable is an object.

**Numbers**

* Python supports two types of numbers: integers and floating point
* Simply assign value to variable \(and Python auto-determines type\) e.g., `intVal=7`  OR `floatVal=7.0`
* Convert integers to floating point using `float()` function

**Strings**

* Defined using single or double quotes
* Simple operators can be executed on numbers and strings \(e.g., + for concatenation\)
* Simultaneous assignment works e.g., `a,b = 3,4`
* Cannot mix number and string types with operator e.g., `one = 1 + "hello" + 2` does not work

## 

## [Lists](http://learnpython.org/en/Lists)

* **Similar to arrays**. Can contain any type of variable & have unlimited number of entries
* Declaration: `mylist = [ ]`
* Add items using **append**: `mylist.append(1)`
* Access items: `mylist[0]` 
* Lists are **0-indexed **\(i.e., index of first element is 0\)

Iterate over list:

```
for x in mylist:
    print(x)
```



