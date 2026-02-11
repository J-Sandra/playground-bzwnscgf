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
# Advanced usage

If you want a more complex example (external libraries, viewers...), use the [Advanced Python template](https://tech.io/select-repo/429)
