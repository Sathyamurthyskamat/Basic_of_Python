>Just when you thought, Python is difficulty try this.

### 1. What is Python?
Python is an interpreted, high-level and general-purpose programming language.
It is used for 

a. Web development,

b. Software development,

c. Mathematics,

d. System scripting.
      
### 2. What can we do using Python?

a. Creation web application(Server-side)

b. Using alongside software to create workflows.
   
c. Connect to database system. Python can also read and modify files.
  
d. Handling big data and perform complex mathematics.
  
e. Rapid prototyping, or for production-ready software development

### 3. Installation of Python

A. Goto https://www.python.org/downloads/ Check your operating system(OS) windows/Linux/UNIX, Mac OS X. Click download.

B. After downloading double click on downloaded file click install.(Check `add to path` option while installing).

C. Installation Done..!

D. Open your commamd promt(command window) (press `winkey+R` type `cmd` and press Enter).

E. In command type `python --version` press Enter key it shows the version of python (Ex: Python 3.7.9).

F. Type `python` and press Enter key. It shows the python version with your machine(computer) information.

G. If you want exit from python type `exit()` and press Enter.
        
  Enjoy.....!!!!
        
### 4. Hello World
This `print()` acts like output. 
```py
>>>print("Hello World!") #Inside the brackets you can write Integer, Float, String.
...
Hello World
```

### 5. Data types in Python 

a. Integers 

An integer is a datum of integral data type, a data type that represents some range of mathematical integers.

Simple meaning Integers contains Number. Ex: 1,67,54 (Numbers)

```py
>>>print(10)
...
10
>>>type(10)
...
<class 'int'>
```
b. Floats 

The FLOAT data type stores double-precision floating-point numbers with up to 17 significant digits. 

Simple meaning  Floats contains double-precision. Ex: 5.0, 5.9,2.5 etc..
```py
>>>print (5.6)
...
5.6
>>>type(3.142)
...
<class 'float'>
```
c. Strings

A string is traditionally a sequence of characters, either as a literal constant or as some kind of variable.

Simple meaning Strings are words, numbers, floats etc in side the `""`
```py
>>>print ("You can enter anything+5") 
...
You can enter anything+5
>>>type("5+10 name")
...
<class 'str'>
```
d. Complex Numbers

Complex numbers are specified as <real part>+<imaginary part>j.
      
```py
>>>2+10j
...
2+10j
>>>type(50+2j)
...
<class 'complex'>
```
e. Boolean Types

Objects of Boolean type may have one of two values, True or False:
```py
>>> type(True)
...
<class 'bool'>
>>> type(False)
...
<class 'bool'>
```
### 6. Variables, Assignment and Expression
#Variables

Variables are name that we give to certain values in our Programs.

#Assignment

The process of storing a values inside a variable is called Assignment.

#Expression

An Expression is a combination of number, symbols or other variables that produce a result when Evaluated.


### 7. Input
This `input()` recives the input form user.
```py
>>> number = input("Enter number/Float/String: ")# You can give integer, Float, String.
>>> print(number)
...
Enter number/Float/String: 2 #Interger Example 2
2
Enter number/Float/String: 3.142 #Interger Example 3.142(pie)
3.142
Enter number/Float/String: sathyamurthy #Interger Example 'Your name'
sathyamurthy
```

### 8. Python Can Use as Calculator
```py
>>> print(5+8) # Adds 5 and 8
...
13.0
>>> print(18/9) # Divides 18 by 9
...
2.0
>>> print(2*60) # Multiplies 2 and 60
...
120.0
>>> print(5-2) # Subtracts 2 from 5
...
3.0
>>> print(((((2500/5)-30)/10)*2)+30) # All operation in one equation
...
124.0
>>> print(4**3) # Elevates 4 to the power of 3. For non integer values of 3, this becomes a root (i.e. 4**(1/2) is the square root of 4)
...
64.0
>>> print(11 % 5) # The remainder part of the integer division of 11 by 5
...
1.0
```

### 9. Functions
We use the `def` keyword for defining a function.
```py
>>>def hello_function(name):
	print("Hello"+name)
>>>hello_function("Sathya")
...
Hello Sathya
```

### 10. Oparators and Boolean Oparators

Oparators:

a. Equal `==` and Not Equal `!=`

b. Less than `>`, More than `<`, Equal and Less than `>=`, Equal and More than `<=`

Boolean Oparators:

a. OR gate `|| or `, AND gate `&& and`, NOT gate `not`.

b. Boolean Oparators can be use as bitwise also,

   OR Gate ` | `, AND gate ` & `, XOR gate ` ^ `, NOT gate ` ~ `.

Two more bit oparators,

Zero fill left shift ` << `

Signed fill right shift ` >> `

### 11. Loops

A. If, Elif and Else Loop: 
	If else Loop can used multiple ways using oparators and boolean oparators. Example below,
 ```py
 
	a = 2
	b = 3
	>>>if a == b:
		print("Both are Equal")
	   else:
		print("Both are not Equal")
	...
	Both are not Equal
	>>>if a != b:
		print("True")
	   else:
		print("False")
	...
	True
	>>>if a < b:
		print("True")
	   else:
		print("False")
	...
	True
	>>>if a > b:
		print("True")
	   else:
		print("False")
	...
	False
	>>>a = 3
	>>>if a <= b:
		print("True")
	   else:
		print("False")
	...
	True
	>>>if a >= b:
		print("True")
	   else:
		print("False")
	...
	True
```
b. While loops
	While Loops Basically Loop will run, over and over again untill `Break` executive.
```py

while (condition) {
  // to be executed
}

a=6
b=1
while (True) {
	// Running
	print("Running")
	if a == b:
		break;
	b=b+1
}
```
c. For loops
	While Loops Basically iterate over a sequence (that is either a list, a tuple, a dictionary, a set, or a string)
