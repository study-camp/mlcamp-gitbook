# Learn Python: Basics

These are notes from the online [Learn Python](http://learnpython.org/) Tutorials. In this section we'll cover the **Basics** portion of those tutorials consisting of the following parts.

* [Hello, World!](http://learnpython.org/en/Hello%2C_World%21)
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

## [Hello World](http://learnpython.org/en/Hello%2C_World%21)

Concepts introduced in this section

* **Print Statement: **print statement in Python3 is a function:  `print("Hello world!"`
* **Comments**: use \# for single-line comments
* **Indentation**: Python uses indentation for blocks \(not braces\). Use tabs or spaces to indent.

## [Variables And Types](http://learnpython.org/en/Variables_and_Types)

* Python is not statically typed. You don't need to declare variables \(or their types\) before using them
* Python is object-oriented. Every variable is an object.

**Numbers**

* Python supports two types of numbers: integers and floating point
* Simply assign value to variable \(and Python auto-determines type\) e.g., `intVal=7`  OR `floatVal=7.0`
* Convert integers to floating point using `float()` function

**Strings**

* Defined using single or double quotes
* Simple operators can be executed on numbers and strings \(e.g., + for concatenation\)
* Simultaneous assignment works e.g., `a,b = 3,4`
* Cannot mix number and string types with operator e.g., `one = 1 + "hello" + 2` does not work

## [Lists](http://learnpython.org/en/Lists)

* Similar to arrays.
* Can contain any type of variable & have unlimited number of entries
* Declaration: `mylist = [ ]`
* Add items using **append**: `mylist.append(1)`
* Access items: `mylist[0]` \(note that list is 0-indexed\)

Iterate over list: 

```
for x in mylist:
    print(x)
```



