# Introduction

Python is a high-level programming language that is dynamically typed and interpreted. Python has some similarities to the English language and its syntax allow to write a programs with fewer lines

## Syntax
After installing python, we create a python file by using the .py file extension
### Indentation
Indentation is very important because it indicates a block of code. It's a space at the beginning of a code line. If you ignore the indentation, Python give you a syntax error
For example,

```python runnable
for i in range (5):
print('Hello World!')
```

```python runnable
for i in range (5):
    print('Hello World!')
```
### Variables
A variable can contain values like integer,string,... and it's created the first moment you assing it the value
```python runnable
i = 5.456
m = "hey"
```
If you want to specify the data type or cast a variable, you can do casting, for example
```python runnable
j = 3.14
j = int(j)
print(j)
```
Another remark, if you want to go down to the next line, use the caracter "\n" in print()
With Python, you can assing multiple values in one code line like this
```python runnable
a ,b, c ="3",5,"bonjour"
print("a=",a,"\nb=",b,"\nc=",c)
```
### Python loop
In Python, we have two commands:
- while loops
- for loops

  ### While loop
  As long as condition is true, the loop keep running
  ```python runnable
    i = 1
    while i <= 5:
      print("Hello")
      i+=1
  ```
  It's important to increment the relevant variable to avoid an infinite loop
  ### For loop
  It is used for iterating over a sequence like list,set,string...
  ```python runnable
   l = ["hello","hey",4]
   for x in l:
      print(x)
  ```
  For executing a set of statement with specified number of time, we can use the **range()** function.
  The range() function returns a sequence of numbers, starting from 0 by default, and increments by 1 (by default), the range(4) returns 0,1,2,3 (not including 4).
  However it is possible to specify :
  - the starting value by adding a first parameter: range (2,10)
  - the increment value by adding a third parameter: range(2, 10, 3)
     ```python runnable
       for i in range(2,10,2):
          print(i)
  ```
