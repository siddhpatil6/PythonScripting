# PythonScripting
Basics of Python Scripting <br>

[![](https://github.com/siddhpatil6/PythonScripting/blob/master/pythonScripting.png)





# Sys Module

## Program -

```
import sys

print("System version :", sys.version)

print("System Arugument :", sys.argv)  # arguments follow sys name

```

## Output -

```
System version : 3.7.2 (v3.7.2:9a3ffc0492, Dec 24 2018, 02:44:43) 
[Clang 6.0 (clang-600.0.57)]
System Arugument : ['/Users/siddhantpatil/PycharmProjects/learn/SysModule.py']
```


# OS Module

## Program
```
import os

print("Current working directory :",os.getcwd())

# now we here changed working directory
os.chdir("/Users/siddhantpatil/Desktop/python")

# get current directory
print("New Current working directory :",os.getcwd())
```

## Outout
```
Current working directory : /Users/siddhantpatil/PycharmProjects/learn
New Current working directory : /Users/siddhantpatil/Desktop/python
```


