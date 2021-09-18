# **<center> GE8151 PROBLEM SOLVING AND PYTHON PROGRAMMING </center>**
![compiler and interpreter](./img/wc.png)
## <center>**UNIT I ALGORITHMIC PROBLEM SOLVING**</center>
<div align="justify"><p><i>Algorithms - building blocks of algorithms (instruction/statements, state, control flow, functions) - notation (pseudo code, flowchart, programming language) </b> algorithmic problem solving, simple strategies for developing algorithms (iteration, recursion)
</div></p></i>
<p><div align="justify"><b><i>Illustrative programs: find minimum in a list, insert a card in a list of sorted cards, guess an integer number in a range, Towers of Hanoi.</b></i></p>

https://www.memcode.com/courses/2283 - 20+ flashcards to review the contents of this unit.# UNIT - 1

>## **Table of Contents**
***
1.1. [Algorithms](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#python-interpreter)

1.2. [Building blocks of Algorithms ](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#variables)
   - [Statements](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#variable-naming-rules-in-python) 
   - [State](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#how-to-declare-and-use-a-variable)
   - [Control flow](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#re-declare-a-variable)
   - [Functions](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#concatenate-variables)
     
1.3. [Notation](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#values-and-types)
   - [Pseudocode](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#data-types)
   - [Flow Chart](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#numeric-type)
     - [Integers](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#integers) 
     - [Boolean](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#boolean)
     - [Float](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#float)
     - [Complex Number](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#complex-number)
   - [Programming Language](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#sequence-type)
     - [String](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#string) 
     - [Escape Sequences](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#escape-sequences)
     
  
1.4. [Algorithmic Problem Solving](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#expressions)
     
1.5. [Simple strategies for developing Algorithms](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#statements)
     - [Iteration](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#list)
     - [Recursion](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#tuple)

1.6. [Illustrative problems](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#arithmetic-operators)
   - [Find minimum in a list](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#arithmetic-operators)
   - [Insert a card in a list of sorted cards](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#comparison-operators)
   - [Guess an integer number in a range](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#logical-operators)
   - [Towers of Hanoi](https://github.com/ProfessorAmbika/UNIT-2-DATA-EXPRESSIONS-STATEMENTS-MATERIAL/blob/main/md/DATA,%20EXPRESSIONS,%20STATEMENTS%20.md#bitwise-operators)
   
>## **Key Terms**
***
* <p><div align="justify"><b><i>Algorithm</b></i>: Algorithm can also be defined a set of rules that precisely defines a sequence of operations. </div></p>
* <p><div align="justify"><b><i>Statement</b></i> A statement is the smallest standalone element of an imperative programming language that expresses some action to be carried out. </div></p>
* <div align="justify"><b><i><p>Control Flow</b></i> is the order in which individual statements, instructions or function calls of an imperative program are executed or evaluated. </div></p>
* <p><div align="justify"><b><i>Pseudocode</b></i> Pseudocode is an artificial and informal language that helps programmers develop algorithms. </div></p>
* <p><div align="justify"><b><i>Flowcharts</b></i> Flowcharts are a graphical means of representing an algorithm. </div></p>

>## **Algorithmic Problem Solving**
***
## **<u>Algorithm</u>**
<p><div align="justify">In mathematics and computer science, an algorithm is a self-contained sequence of actions to be performed. 
Algorithm can also be defined a set of rules that precisely defines a sequence of operations.
Algorithms can perform calculation, data processing and automated reasoning tasks.</div></p>

**Real Life Example**<br/>
Procedure to cook Bread Toast
```
Step 1: Grab a loaf of bread
Step 2: Get a pan and place it on the stove let it heat
Step 3: Pour some oil on the pan and wait for oil to be heated
Step 4: Put a slice on the pan and roast until it become brown in shade
Step 5: Turn the slice and roast until it become brown in shade
Step 6: Get the toasted bread from the pan and serve it on a plate with anything or nothing

The above procedure that explains “how to make a bread toast” and what are all the requirements before we start the 
procedures. We can code this procedure or algorithm in any programing language of your choice and simulate as results
on the computer display. Else we can feed this procedure to the robot with proper instructions and we make the robot 
to do the bread toast for us.
```

**Example :**<br/>
Algorithm for adding two numbers:
```
Step 1 : Get the 2 numbers from the user as input.
Step 2 : Perform addition of those 2 numbers.
Step 3 : Store the answer for display.
Step 4 : Display the stored value to the user.
```

## Qualities of an Algorithm
- **Accuracy**: Algorithm should provide accurate result
- **Memory**: It should require minimum computer memory
- **Time**: It should take finite amount of time.
- **Sequence**: The procedure of an algorithm must be in sequential form

## Characteristics/Properties of Algorithm
**Input**: All the algorithms should have some input. The logic of the algorithm should work on this input to give the desired result.<br />
**Finiteness**: An algorithm must always terminate after a finite number of steps.<br />
**Definiteness**: Every step of the algorithm should be clear and not any ambiguity.<br />
**Effectiveness**: Every step in the algorithm should be easy to understand and can be implemented using any programming language.<br />
**Output**: At least one output should be produced from the algorithm based on the input given.<br />

## Advantage
- It is a stepwise description of a solution, which makes easy to understand.
- It is not dependent on any programming language.
- It is easier for programmer to convert into an actual program.

## Disadvantage
- It is difficult to show branching and looping statements.
- It is time consuming, algorithm needs to be developed first which is then converted to program.

<div align="justify">It was created by Guido van Rossum during <b><i>1985-1990</b></i>. Python got its name from <b><i>“Monty Python’s flying circus”</b></i>. Python was released in the year 2000.</div>

* <p><div align="justify"><b><i>Python is interpreted: </b></i> Python is processed at runtime by the interpreter. You do not need to compile your program before executing it. </div></p>
* <p><div align="justify"><b><i>Python is Interactive: </b></i> You can actually sit at a Python prompt and interact with the interpreter directly to write your programs. </div></p>
* <p><div align="justify"><b><i>Python is Object-Oriented: </b></i> Python supports Object-Oriented style or technique of programming that encapsulates code within objects. </div></p>
* <p><div align="justify"><b><i>Python is a Beginner's Language: </b></i> Python is a great language for the beginner- Level programmers and supports the development of a wide range of applications.</div> </p>
## **<u>Python Features</u>**
* <p><div align="justify"> <b><i>Easy-to-learn: </b></i> Python is clearly defined and easily readable. The structure of the program is very simple. It uses few keywords. </div></p>
* <p><div align="justify"> <b><i>Easy-to-maintain:</b></i> Python's source code is fairly easy-to-maintain. </p></div>
* <p><div align="justify"> <b><i>Portable:</b></i> Python can run on a wide variety of hardware platforms and has the same interface on all platforms. </div></p>
* <p><div align="justify"><b><i>Interpreted:</b></i> Python is processed at runtime by the interpreter. So, there is no need to compile a program before executing it. You can simply run the program. </div></p>
* <p><div align="justify"><b><i>Extensible:</b></i> Programmers can embed python within their C, C++, JavaScript, ActiveX, etc.</div></p> 
* <p><div align="justify"><b><i>Free and Open Source: </b></i> Anyone can freely distribute it, read the source code, and edit it. </div></p>
* <p><div align="justify"><b><i> High Level Language: </b></i> When writing programs, programmers concentrate on solutions of the current problem, no need to worry about the low level details. </div></p>
* <p><div align="justify"><b><i>Scalable:</b></i> Python provides a better structure and support for large programs than shell scripting.</div></p>

## **<u> Python interpreter</u>**
<p><div align="justify"> <b><i>Interpreter:</b></i> An interpreter is a translator (computer program) that repeatedly reads instructions (one at a time) and translates them to machine code. It then executes instructions written in a programming or scripting language, without requiring them previously to have been compiled into a machine language program. </div></p>

<div align="justify"> <b><i>Compiler:</b></i> To translate a program written in a high-level language into a low-level language all at once, in preparation for later execution. </div> </p>

![compiler and interpreter](./img/1.png)
## **<u> Difference between Compiler and Interpreter</u>**
| Compiler | Interpreter |
| --- | ----------- |
| <div align="justify"> Scans the entire program and translates it as a whole into machine code. </div> | <div align="justify">Translates program one statement at a time. </div>|
| <div align="justify"> It takes large amount of time to analyze the source code but the overall execution time is comparatively faster. </div> | <div align="justify"> It takes less amount of time to analyze the source code but the overall execution time is slower. </div> |
| <div align="justify"> Generates intermediate object code which further requires linking, hence requires more memory. </div> | <div align="justify"> No intermediate object code is generated, hence are memory efficient. </div> |
| <div align="justify"> It generates the error message only after scanning the whole program. Hence debugging is comparatively hard. </div> | <div align="justify"> Continues translating the program until the first error is met, in which case it stops. Hence debugging is easy. </div>|
| <div align="justify"> Programming language like C, C++ uses compilers. </div> | <div align="justify"> Programming languages like Python, Ruby use interpreters. </div> |
## **Modes of Python Interpreter** 
Python has two basic modes: script and interactive.

###  **_1. Interactive Mode:_**
<p><div align="justify">Interactive mode is a command line shell which gives immediate feedback for each statement, while running previously fed statements in active memory. As new lines are fed into the interpreter, the fed program is evaluated both in part and in whole.</div></p>
<p><div align="justify">The code executes via the Python shell, which comes with Python installation. Interactive mode is handy when you just want to execute basic Python commands or you are new to Python programming. </div></p>
<p><div align="justify">To access the Python shell, open the terminal of your operating system and then type "python". Press the enter key and the Python shell will appear.</div></p>

![python cmd](./img/2.PNG)

<p><div align="justify"> The >>> indicates that the Python shell is ready to execute and send your commands to the Python interpreter. The result is immediately displayed on the Python shell as soon as the Python interpreter interprets the command. </div></p>
<p><div align="justify">To run your Python statements, just type them and hit the enter key. You will get the results immediately, unlike in script mode. For example, to print the text "Hello World", we can type the following:</div></p>

```python
>>> print("Hello World")
Hello World
```

```python
>>> 10
10
>>> print(5*20)
100
>>> "hi" * 5
'hihihihihi'
>>>
``` 
<div align="justify"> It is possible to run multiple Python statements without having to create and save a script. You can also copy your code from another source then paste it on the Python shell. </div>

```python
>>> the_world_is_flat = True
>>> if the_world_is_flat:
        print("Be careful not to fall off!")

Be careful not to fall off
```
### <b><i>Advantages of Interactive Mode</b></i>
* <p><div align="justify"> Helpful when the script is extremely short and wants immediate results. </div></p>
* <p><div align="justify"> Faster as you only have to type a command and then press the enter key to get the results. </div></p>
* <p><div align="justify"> Good for beginners who need to understand Python basics. </div></p>
### **_Disadvantages of Interactive Mode_**
* <p><div align="justify"> Editing the code in interactive mode is hard to move back to the previous commands or else the whole command has to be rewritten again. </div></p>
* <p><div align="justify"> It's very tedious to run long pieces of code. </div><p>
### **_2. Script Mode:_**
<p><div align="justify"> In script mode, we type python program in a file and then use interpreter to execute the content of the file. Scripts can be saved to disk for future use. Python scripts have the extension .py, meaning that the filename ends with     <i><b>.py</i></b>. Save the code with <i><b>filename.py</i></b> and run the interpreter in script mode to execute the script. </div></p>
<p><div align="justify"> In the standard Python shell, click <i><b>"File"</i></b> then choose <i><b>"New"</i></b> or simply hit <i><b>"Ctrl + N"</i></b> on your keyboard to open a blank script in which you can write your code. You can then press <i><b>"Ctrl + S"</i></b> to save it. </div><p>
<p><div align="justify"> After writing your code, run it by clicking <i><b>"Run"</i></b> then "Run Module" or simply <i><b>press F5</i></b>. </div><p>

![python cmd](./img/4.png)

![python cmd](./img/5.png)

![python cmd](./img/6.png)

### **_Advantages of Script Mode_**
* It is easy to run large pieces of code.
* Editing your script is easier in script mode.
* Good for both beginners and experts.
### **_Disadvantages of Script Mode_**
* Can be tedious when you need to run only a single or a few lines of code.
* Must create and save a file before executing your code.
>## **Variables**
***
<p><div align="justify">A Python variable is a reserved memory location to store values. In other words, a variable in a python program gives data to the computer for processing.</div></p>
<p><div align="justify">Every value in Python has a datatype. Different data types in Python are Numbers,
List, Tuple, Strings, Dictionary, etc. Variables can be declared by any name or even alphabets like a, aa, abc, etc. </p></div>

## **_Variable Naming Rules in Python_** 
* <p><div align="justify"> Variable name should start with letter(a-zA-Z) or underscore ( _ ). </p></div> <b>Valid : age , _age , Age <p>Invalid : 1age</p></b>
* <p><div align="justify">In variable name, no special characters allowed other than underscore ( _ ). </p></div> <b>Valid : age_ , _age <p>Invalid : age_*</p></b>
* <p><div align="justify">Variables are case sensitive.</p> </div><b>age and Age are different, since variable names are case sensitive</b>
* <p><div align="justify">Variable name can have numbers but not at the beginning.</p></div> <b>Example: Age1**</b>
* <p><div align="justify">Variable name should not be a Python keyword. Keywords are also called as reserved words.</p></div> <b>Example: pass, break, continue.. etc are reserved for special meaning in Python. So, we should not declare keyword as a variable name. </b>
## **_How to Declare and use a Variable_** 
<p><div align="justify">Let see an example. We will declare variable "a" and print it</div></p>

```python
>>>a=100
>>>print(a)
```
### **Output**
100

## **_Re-declare a Variable_** 
<p><div align="justify">You can re-declare the variable even after you have declared it once.</p></div>

```python
>>>a=100
>>>print(a)
>>>a=’Python’
>>>print(a)
```
### **Output**
100 <p></p> Python

## **_Concatenate Variables_**
```python
>>>a='ABS'
>>>b=1
>>>print(a+b)
```
**Output**
```python
Traceback (most recent call last):
  File "<pyshell#2>", line 1, in <module>
    print(a+b)
TypeError: can only concatenate str (not "int") to str
```
```python
>>> a='ABS'
>>> b=1
>>> print(a+str(b))
```
**Output**
```
ABS1
```
## **_Delete a variable_**
<p><div align="justify">It is possible to delete variable using the command del "variable name".</p></div>

>## **Values and Types**
***
## **Data Types**
<p><div align="justify">Data types are the <i>classification or categorization of data items</i>. Python supports the following built-in data types</div></p>

* Numeric
* Sequence Type
* Boolean
* Set
* Dictionary

![python cmd](./img/datatypes.PNG)

## **Numeric Type**
## **_Integers_**
<p><div align="justify">This value is represented by int class. It contains positive or negative whole numbers (without fraction or decimal). In Python there is no limit to how long an integer value can be. The followings are valid integer literals in Python.</p></div>

``` python
>>> 0
0
>>> 100
100
>>> -10
10
>>> 1234567890
1234567890
>>>y=5000000000000000000000000000000000000000000000000000000
>>>y
5000000000000000000000000000000000000000000000000000000
```

<p><div align="justify">Integers can be binary, octal, and hexadecimal values.</p><div>

```python
>>> 0b11011000 # binary
216
>>> 0o12 # octal
10
>>> 0x12 # hexadecimal
15
```
<p><div align="justify">All integer literals or variables are objects of the int class. Use the type() method to get the class name, as shown below.</p></div>

```python
>>>type(100)
<class 'int'> 

>>> x=1234567890
>>> type(x)
<class 'int'> 

>>>y=5000000000000000000000000000000000000000000000000000000
>>> type(y) 
<class 'int'>
```
<p><div align="justify">Leading zeros in non-zero integers are not allowed e.g. 000123 is invalid number, 0000 is 0.</p></div>

```python
>>> 01234
  File "<stdin>", line 1
    01234
        ^
SyntaxError: leading zeros in decimal integer literals are not permitted; use an 0o prefix for octal integers
```
<p><div align="justify">Python does not allow comma as number delimiter. Use underscore _ as a delimiter instead.</p></div>

```python
>>> x=1_234_567_890
>>> x
1234567890
```
<p><div align="justify">The <b><i>int( )</b></i> function converts a string or float to int.</p></div>

```python
>>> int('100')
100
>>> int('-10')
-10
>>> int('5.5')
5
>>> int('100', 2)
4
```
## **_Boolean_**
<p><div align="justify">Data type with one of the two built-in values, True or False. Boolean objects that are equal to True are truthy (true), and those equal to False are falsy (false). But non-Boolean objects can be evaluated in Boolean context as well and determined to be true or false. It is denoted by the <b><i>class bool</b></i>.True and False with capital <b><i>‘T’ and ‘F’</b></i> are valid booleans otherwise python will throw an error.</p></div>

```python
>>>print(type(True))
<class 'bool'>
>>>print(type(False))
<class 'bool'>

print(type(true))
Traceback (most recent call last):
  File "<stdin>", line 1, in <module>
NameError: name 'true' is not defined
```
## **_Float_**
<p><div align="justify"> In Python, floating point numbers (float) are positive and negative real numbers with a fractional part denoted by the decimal symbol . or the scientific notation E or e, <b>e.g. 1234.56, 3.142, -1.55, 0.23.</b></p></div>

```python
>>> f=3.12
>>> f
3.12
>>> type(f)
<class 'float'>
```
<p><div align="justify">Floats can be separated by the underscore _, <b>e.g. 123_42.222_013</b> is a valid float.</p> </div>

```python
>>> f=123_42.222_013
>>> f
12342.222013
```
<p><div align="justify">Floats has the maximum size depends on your system. The float beyond its maximum size referred as <b>"inf", "Inf", "INFINITY", or "infinity".</b> <b> Float 2e400</b> will be considered as infinity for most systems.</p> </div>

```python
>>> f=2e400
>>> f
inf
```
## **_Complex Number_**
<p><div align="justify">A complex number is a number with real and imaginary components. For example, 5 + 6j is a complex number where 5 is the real component and 6 multiplied by j is an imaginary component.</p></div>

```python
>>> a=7+3j
>>> a
(7+3j)
>>> type(a)
<class 'complex'>
```
<p><div align="justify">You must use <b>j or J</b> as imaginary component. Using other character will throw syntax error.</p></div>

```python
>>> a=5+2k
SyntaxError: invalid syntax
>>> a=5+j
SyntaxError: invalid syntax
>>> a=5j+2j
SyntaxError: invalid syntax
```
## **Sequence Type**
<p><div align="justify">In Python, sequence is the ordered collection of similar or different data types. Sequences allows to store multiple values in an organized and efficient fashion. There are several sequence types in Python</p></div>

* String
* List
* Tuple
## **_String_**
<p><div align="justify">In Python, string is an immutable sequence data type. It is the sequence of Unicode characters wrapped inside single, double, or triple quotes.</p></div>

```python
'This is a string in Python' # string in single quotes
"This is a string in Python" # string in double quotes
'''This is a string in Python''' # string in triple quotes
"""This is a string in Python""" # string in triple double-quotes
```
**Example:** https://replit.com/@ErAmbikaM/String1#main.py

<p><div align="justify">Multi-line strings must be embed in triple quotes, as shown below.</p></div>

**Example:** https://replit.com/@ErAmbikaM/Multiline-String#main.py

<p><div align="justify">Use the len() function to retrieve the length of a string, as shown below.</p></div>

```python
>>> wish='Hello'
>>> len(wish)
5
```
<p><div align="justify">In Python, individual characters of a String can be accessed by using the method of Indexing. </p></div>

![python cmd](./img/str.png)
```python
>>> wish='Hello'
>>> wish[0]
'H'
>>> wish[1]
'e'
>>> wish[4]
'o'
>>> wish[5]
Traceback (most recent call last):
  File "<pyshell#6>", line 1, in <module>
    wish[5]
IndexError: string index out of range
```
<p><div align="justify">Indexing allows negative address references to access characters from the back of the String, e.g. -1 refers to the last character, -2 refers to the second last character and so on.</p></div>

```python
>>> wish='Hello'
>>> wish[-5]
'H'
>>> wish[-2]
'l'
>>> wish[-3]
'l'
>>> wish[-6]
Traceback (most recent call last):
  File "<pyshell#13>", line 1, in <module>
    wish[-6]
IndexError: string index out of range
>>> 
```
<p><div align="justify">The string is an immutable object. Hence, it is not possible to modify it. The attempt to assign different characters at a certain index results in errors.</p></div>

```python
>>> wish='hello'
>>> wish[0]='B'
Traceback (most recent call last):
  File "<pyshell#26>", line 1, in <module>
    wish[0]='B'
TypeError: 'str' object does not support item assignment
```
<p><div align="justify">All strings are objects of the <b><i>str class</b></i> in Python.

```python
>>> wish='hello'
>>> type(wish)
<class 'str'>
```
## **_Escape Sequences_**
<p><div align="justify">The escape character is used to invoke an alternative implementation of the subsequent character in a sequence.</p></div>

```python
>>> str1='Welcome to \'Python Tutorial\' '
>>> print(str1)
Welcome to 'Python Tutorial' 

>>> str1='Welcome to \"Python Tutorial\" '
>>> print(str1)
Welcome to "Python Tutorial" 
```
| Escape Sequence | Description | Example |
| ----------- | ----------- | ----------- |
| <div align="center"> \\\ </div> | <div align="justify">Backslash </div>| <div>>>> "Hello\\Hi"</div> Hello\Hi   | 
| <div align="center"> \b </div> | <div align="justify">Backspace </div>| <div>>>> "ab\bc"</div> ac | 
| <div align="center"> \f </div> | <div align="justify">Form feed </div>|  | 
| <div align="center"> \n </div> | <div align="justify">Newline </div>| <div>>>> "hello\nworld"</div> <div>Hello </div>world | 
| <div align="center"> \nnn </div> | <div align="justify">Octal notation, where n is in the range 0-7 </div>| <div>>>> '\101'</div> A | 
| <div align="center"> \t </div> | <div align="justify">Tab </div>| <div> >>>'Hello\tPython'</div> Hello &nbsp; &nbsp; &nbsp; &nbsp; Python |
| <div align="center"> \xnn </div> | <div align="justify">Hexadecimal notation, where n is in the range 0-9, a-f, or A-F </div>| <div> >>> '\x48\x69'</div> Hi |
| <div align="center"> \onn </div> | <div align="justify">Octal notation, where n is in the range 0-9 </div>| <div> >>> "\110\151"</div> Hi 
## **_List_**
<p><div align="justify">Lists are just like the arrays, declared in other languages which is a ordered collection of data. It is very flexible as the items in a list do not need to be of the same type.</div></p>

**Creating a List**
Lists in Python can be created by just placing the sequence inside the square brackets[].

**Example:** https://replit.com/@ErAmbikaM/List1#main.py

<p><div align="justify">A list can contain unlimited data depending upon the limitation of your computer's memory.</div></p>

```python
nums=[1,2,3,4,5,6,7,8,9,10,11,12,13,14,15,16,17,18,19,20, 21,22,23,24,25,26,27,28,29,30,31,32,33,34,35,36,37,38,39,40,41,42,43,44,45,46,47,48,49,50,51,52,53,54,55,56,57,58,59,60]
```
<p><div align="justify">List items can be accessed using a zero-based index in the square brackets [ ]. Indexes start from zero and increment by one for each item. Accessing an item using a large index than the list's total items would result in IndexError. </div></p>

**Example:** https://replit.com/@ErAmbikaM/accessinglist#main.py

<p><div align="justify">A list can contain multiple inner lists as items that can be accessed using indexes.</p></div>

**Example:** https://replit.com/@ErAmbikaM/innerlist#main.py
## **_Tuple_**
<p><div align="justify">Tuple is an immutable (unchangeable) collection of elements of different data types. It is an ordered collection, so it preserves the order of elements in which they were defined.</p></div>
<p><div align="justify">Tuples are defined by enclosing elements in parentheses ( ), separated by a comma. The following declares a tuple type variable. </p></div>

**Example: Tuple Variable Declaration and assignment**
```python
tpl=() # empty tuple
print(tpl)

names = ('Jeff', 'Bill', 'Steve', 'Yash') # string tuple
print(names)

nums = (1, 2, 3, 4, 5) # int tuple
print(nums)

employee=(1, 'Steve', True, 25, 12000)  # heterogeneous data tuple
print(employee)
```
**Output**

![tuple example](./img/7.png)
<p><div align="justify">It is not necessary to enclose the tuple elements in parentheses. The tuple object can include elements separated by a comma without parentheses.</div></p>

```python
names = 'Jeff', 'Bill', 'Steve', 'Yash' # string tuple
print(names)

nums = 1, 2, 3, 4, 5 # int tuple
print(nums)

employee=1, 'Steve', True, 25, 12000  # heterogeneous data tuple
print(employee)
```
**Output**
![tuple example](./img/8.png)
<p><div align="justify">Tuples cannot be declared with a single element unless followed by a comma.</div></p>

```python
names = ('Jeff') # considered as string type
print(names)
print(type(names))

names = ('Jeff',) # tuple with single element
print(names)
print(type(names))
```
**Output**

![tuple example](./img/9.png)
**Access Tuple Elements**
<p><div align="justify">Each element in the tuple is accessed by the index in the square brackets [ ]. An index starts with zero and ends with (number of elements - 1), as shown below.</p></div>

**Example**
```python
names = ('Jeff', 'Bill', 'Steve', 'Yash') 
print(names[0]) 
print(names[1]) 
print(names[2]) 
print(names[3]) 

nums = (1, 2, 3, 4, 5) 
print(nums[0]) 
print(nums[1]) 
print(nums[4]) 
```
**Output**

![tuple access](./img/10.png)
<p><div align="justify">The tuple supports negative indexing also, the same as list type. The negative index for the first element starts from -number of elements and ends with -1 for the last element.</p></div>

**Example**
```python
names = ('Jeff', 'Bill', 'Steve', 'Yash') 
print(names[-4]) 
print(names[-3]) 
print(names[-2]) 
print(names[-1]) 
```
**Output**

![tuple access](./img/11.png)
<p><div align="justify">Tuple elements can be unpacked and assigned to variables, as shown below. However, the number of variables must match with the number of elements in a tuple; otherwise, an error will be thrown.</p></div>

**Example**
```python
names = ('Jeff', 'Bill', 'Steve', 'Yash') 
a, b, c, d = names # unpack tuple
print(a, b, c, d)
```
**Output**
![tuple access](./img/12.png)
>## **Expressions**
***
<p><div align="justify">A simple example of an expression is 2 + 3. An expression can be broken down into operators and operands.</p></div> 
<p><div align="justify">An expression is a combination of values, variables, operators, and calls to functions. Expressions need to be evaluated. If you ask Python to print an expression, the interpreter evaluates the expression and displays the result. </p></div>

>## **Statements**
***
<p><div align="justify">
Instructions written in the source code for execution are called statements. There are different types of statements in the Python programming language like Assignment statements, Conditional statements, Looping statements, etc. These all help the user to get the required output. For example, n = 50 is an assignment statement. </p></div>
<b><p><div align="justify">Multi-Line Statements:</b> Statements in Python can be extended to one or more lines using parentheses (), braces {}, square brackets [], semi-colon (;), continuation character slash (\). When the programmer needs to do long calculations and cannot fit his statements into one line, one can make use of these characters.  </p></div>

**Example**
```python
#Declared using Continuation Character (\):
s = 1 + 2 + 3 + \
    4 + 5 + 6 + \
    7 + 8 + 9

#Declared using parentheses () :
n = (1 * 2 * 3 + 7 + 8 + 9)

#Declared using square brackets [] :
footballer = ['MESSI',
          'NEYMAR',
          'SUAREZ']

#Declared using braces {} :
x = {1 + 2 + 3 + 4 + 5 + 6 +
     7 + 8 + 9}

#Declared using semicolons(;) :
flag = 2; ropes = 3; pole = 4
```
>## **Operators**
***
<p><div align="justify">Operators are special symbols in Python that carry out arithmetic or logical computation. The value that the operator operates on is called the operand.</p></div>

## **_Arithmetic operators_**
<p><div align="justify">Arithmetic operators are used to perform mathematical operations like addition, subtraction, multiplication, etc.</p></div>

| Operator | Meaning | Example |
| ----------- | ----------- | ----------- |
| <div align="center"> + </div> | <div align="justify">Add two operands or unary plus </div>| x + y + 2  |
| <div align="center"> - </div> | <div align="justify">Subtract right operand from the left or unary minus </div>| x - y - 2  |
| <div align="center"> * </div> | <div align="justify">Multiply two operands </div>| x * y  |
| <div align="center"> / </div> | <div align="justify">Divide left operand by the right one (always results into float) </div>| x / y |
| <div align="center"> % </div> | <div align="justify">Modulus - remainder of the division of left operand by the right </div>| x % y (remainder of x/y) |
| <div align="center"> // </div> | <div align="justify">Floor division - division that results into whole number adjusted to the left in the number line </div>| x // y |
| <div align="center"> ** </div> | <div align="justify">Exponent - left operand raised to the power of right </div>| x**y (x to the power y) |

**Example:** https://replit.com/@ErAmbikaM/arithmeticoperator#main.py
## **_Comparison operators_**
<p><div align="justify">Comparison operators are used to compare values. It returns either True or False according to the condition.</p></div>

| Operator | Meaning | Example |
| ----------- | ----------- | ----------- |
| <div align="center"> > </div> | <div align="justify">Greater than - True if left operand is greater than the right </div>| x > y  |
| <div align="center"> < </div> | <div align="justify">Less than - True if left operand is less than the right </div>| x < y  |
| <div align="center"> == </div> | <div align="justify">Equal to - True if both operands are equal </div>| x == y  |
| <div align="center"> != </div> | <div align="justify">Not equal to - True if operands are not equal </div>| x != y  |
| <div align="center"> >= </div> | <div align="justify">Greater than or equal to - True if left operand is greater than or equal to the right </div>| x >= y  |
| <div align="center"> <= </div> | <div align="justify">Less than or equal to - True if left operand is less than or equal to the right </div>| x <= y  |

**Example:** https://replit.com/@ErAmbikaM/Comparisonoperator#main.py

## **_Logical operators_**
<p><div align="justify">Logical operators are the and, or, not operators.</p></div>

| Operator | Meaning | Example |
| ----------- | ----------- | ----------- |
| <div align="center">and </div> | <div align="justify">True if both the operands are true </div>| x and y |
| <div align="center">or </div> | <div align="justify">True if either of the operands is true </div>| x or y |

**Example:** https://replit.com/@ErAmbikaM/Logicaloperator#main.py

## **_Bitwise operators_**
<p><div align="justify">Bitwise operators act on operands as if they were strings of binary digits. They operate bit by bit, hence the name.</p></div>
<p><div align="justify">In the table below: Let x = 10 (0000 1010 in binary) and y = 4 (0000 0100 in binary)</p></div>

| Operator | Meaning | Example |
| ----------- | ----------- | ----------- |
| <div align="center">& </div> | <div align="justify">Bitwise AND </div>| x & y = 0 (0000 0000) |
| <div align="center">\|</div> | <div align="justify">Bitwise OR </div>| x \| y = 14 (0000 1110) |
| <div align="center">~</div> | <div align="justify">Bitwise NOT </div>| ~x = -11 (1111 0101) |
| <div align="center">^</div> | <div align="justify">Bitwise XOR </div>| x ^ y = 14 (0000 1110) |
| <div align="center">>></div> | <div align="justify">Bitwise right shift </div>| x >> 2 = 2 (0000 0010) |
| <div align="center"><<</div> | <div align="justify">Bitwise left shift </div>| x << 2 = 40 (0010 1000) |
## **_Assignment operators_**
<p><div align="justify">Assignment operators are used in Python to assign values to variables. a = 5 is a simple assignment operator that assigns the value 5 on the right to the variable a on the left.</p></div>

| Operator | Example | Equivalent to |
| ----------- | ----------- | ----------- |
| <div align="center">= </div> | <div align="center">x = 5 </div>|<div align="center"> x = 5 </div> |
| <div align="center">+= </div> | <div align="center">x += 5 </div>|<div align="center"> x = x + 5 </div> |
| <div align="center">-= </div> | <div align="center"> x -= 5 </div>|<div align="center"> x = x - 5 </div> |
| <div align="center">*= </div> | <div align="center"> x *= 5 </div>|<div align="center"> x = x * 5 </div> |
| <div align="center">/= </div> | <div align="center"> x /= 5 </div>|<div align="center"> x = x / 5 </div> |
| <div align="center">%=</div> | <div align="center"> x %= 5 </div>|<div align="center"> x = x % 5 </div> |
| <div align="center">//=</div> | <div align="center"> x //= 5 </div>|<div align="center"> x = x // 5 </div> |
| <div align="center">**=</div> | <div align="center"> x **= 5 </div>|<div align="center"> x = x ** 5 </div> |
| <div align="center">&=</div> | <div align="center"> x &= 5 </div>|<div align="center"> x = x & 5 </div> |
| <div align="center">\|=</div> | <div align="center"> x \|= 5 </div>|<div align="center"> x = x \| 5 </div> |
| <div align="center">^=</div> | <div align="center"> x ^= 5 </div>|<div align="center"> x = x ^ 5 </div> |
| <div align="center">>>=</div> | <div align="center"> x >>= 5 </div>|<div align="center"> x = x >> 5 </div> |
| <div align="center"><<=</div> | <div align="center"> x <<= 5</div>|<div align="center"> x = x << 5</div> |
## **_Special operators_**
<p><div align="justify">Python language offers some special types of operators like the identity operator or the membership operator. </p></div>

### **_Identity operators_**
<p><div align="justify"> <b>is and is not</b> are the identity operators in Python. They are used to check if two values (or variables) are located on the same part of the memory. Two variables that are equal does not imply that they are identical.

| Operator | Meaning | Example |
| ----------- | ----------- | ----------- |
| <div align="center">is </div> | <div align="justify">True if the operands are identical (refer to the same object) </div>|<div align="center"> x is True </div> |
| <div align="center">is not </div> | <div align="justify">True if the operands are identical (refer to the same object) </div>|<div align="center"> x is not True </div> |

**Example:** https://replit.com/@ErAmbikaM/identity-operator#main.py

### **_Membership operators_**
<p><div align="justify">in and not in are the membership operators in Python. They are used to test whether a value or variable is found in a sequence (string, list, tuple, set and dictionary). In a dictionary we can only test for presence of key, not the value.</p></div>

| Operator | Meaning | Example |
| ----------- | ----------- | ----------- |
| <div align="center">in </div> | <div align="justify">True if value/variable is found in the sequence </div>|<div align="center"> 5 in x </div> |
| <div align="center">not in</div> | <div align="justify">True if value/variable is not found in the sequence </div>|<div align="center"> 5 not in x </div> |

**Example:** https://replit.com/@ErAmbikaM/membershipoperator#main.py

>## **Precedence of operators**
<p><div align="justify">The following figure lists all operators from highest precedence to lowest.</p></div>

![tuple access](./img/13.PNG)

>## **Comments**
<p><div align="justify">Comments are lines that exist in computer programs that are ignored by compilers and interpreters. Using comments in programs can make code more readable for humans, as it provides some information or explanation about what each part of a program is doing.</p></div>

### **_Single-Line Comments in Python_**
<p><div align="justify">In Python, we use the hash symbol # to write a single-line comment.</p></div>

```python
# printing a string
print('Hello world')
```
Here, the comment is: **# printing a string**

### **_Multi-Line Comments in Python_**
<p><div align="justify">Python doesn't offer a separate way to write multiline comments. However, there are other ways to get around this issue.

**Using multiple #**
```python
# it is a
# multiline
# comment
```
**String Literals for Multi-line Comments**
```python
#this is a comment
'this is an unassigned string as a comment '
```
**Using String Literals to write Multi-line Comments**
```python
'''
I am a
multiline comment!

'''
print("Hello World")
```
>## **Modules**
<p><div align="justify">Consider a module to be the same as a code library. A file containing a set of functions you want to include in your application. </p></div>

**Create a Module**

<p><div align="justify">To create a module just save the code you want in a file with the file extension .py. Save this code in a file named mymodule.py</p></div>

```python
def greeting(name):
  print("Hello, " + name)
```
**Use a Module**
<p><div align="justify">Now we can use the module we just created, by using the import statement. Import the module named mymodule, and call the greeting function.</p></div>

```python
import mymodule
mymodule.greeting("Stephen")
```
**Output**
```
Hello Stephen
```
**Variables in Module**
<p><div align="justify">The module can contain functions, as already described, but also variables of all types (arrays, dictionaries, objects etc).</p></div>
<p>Save this code in the file mymodule.py</p>

```python
person1 = {
  "name": "John",
  "age": 36,
  "country": "Norway"
}
```
<p><div align="justify">Import the module named mymodule, and access the person1 dictionary.</p></div>

```python
import mymodule

a = mymodule.person1["age"]
print(a)
```
**Output**
```
36
```
>## **Functions**
<p><div align="justify">Python Functions is a block of related statements designed to perform a computational, logical, or evaluative task. The idea is to put some commonly or repeatedly done tasks together and make a function so that instead of writing the same code again and again for different inputs, we can do the function calls to reuse code contained in it over and over again. </p></div>

* <p><div align="justify"> Function blocks begin with the keyword <b>def</b> followed by the function name and parentheses ( ( ) ). </p></div>
* <p><div align="justify"> Any input parameters or arguments should be placed within these parentheses. You can also define parameters inside these parentheses. </p></div>
* <p><div align="justify"> The first statement of a function can be an optional statement - the documentation string of the function or docstring. </p></div>
* <p><div align="justify">The code block within every function starts with a colon (:) and is indented. </p></div>
* <p><div align="justify">The statement return [expression] exits a function, optionally passing back an expression to the caller. A return statement with no arguments is the same as return None.

<p><div align="justify">Functions can be both built-in or user-defined. It helps the program to be concise, non-repetitive, and organized.</p></div>

**Syntax:**

```python
def function_name(parameters):
    """docstring"""
    statement(s)
    return expression
```
>## **Function Definition and Use**
**_Creating a Function_**
<p><div align="justify">In Python a function is defined using the def keyword:</p></div>

```python
def my_function():
  print("Hello from a function")
```
**_Calling a Function_**
<p><div align="justify">To call a function, use the function name followed by parenthesis:</p></div>

```python
def my_function():
  print("Hello from a function")

my_function()
```
**Example:** https://replit.com/@ErAmbikaM/functionexample#main.py

>## **Flow of Execution**
<p><div align="justify">The flow of execution basically refers to the order in which statements are executed. That is to say, execution always starts at the first statement of the program. Moreover, statements execute one at a time. It happens in order, from top to bottom.</p></div>
<p><div align="justify">Further, functions definitions do not alter the flow of execution of the program. However, it remembers the statements inside the function do not execute until the functions is called.</p></div>
<p><div align="justify">Moreover, function calls are similar to a bypass in the flow of execution. Thus, in place of going to the next statement, the flow will jump to the first line of the called function. Then, it will execute all the statements there. After that, it will come back to pick up where it left off.</p></div>
<p><div align="justify">It is essential to remember that when reading a program, do not read it from top to bottom. Instead, keep following the flow of execution. This will ensure that one reads the def statements as they are scanning from top to bottom.</p></div>

![tuple access](./img/15.png)

![tuple access](./img/14.png)

>## **Parameters and Arguments**
<p><div align="justify">The terms parameter and argument can be used for the same thing: information that are passed into a function.</p></div>

* <p><div align="justify">The terms parameter and argument can be used for the same thing: information that are passed into a function.</p></div>
* <p><div align="justify">A parameter is the variable listed inside the parentheses in the function definition.</p></div>
* <p><div align="justify">An argument is the value that is sent to the function when it is called.</p></div>

**_Number of Arguments_**
<p><div align="justify">By default, a function must be called with the correct number of arguments. Meaning that if your function expects 2 arguments, you have to call the function with 2 arguments, not more, and not less.</p></div>

**_Types of Arguments_**

<p><div align="justify">You can call a function by using the following types of formal arguments −</p></div>

* Required arguments
* Keyword arguments
* Default arguments
* Variable-length arguments

**_Required Arguments_**
* <p><div align="justify">Required arguments are the arguments passed to a function in correct positional order. </p></div>
* <p><div align="justify">Here, the number of arguments in the function call should match exactly with the function definition. </p></div>

**Example:** https://replit.com/@ErAmbikaM/RequiredArguments#main.py

**_Keyword Arguments_**
* <p><div align="justify">Keyword arguments are related to the function calls. 
* <p><div align="justify">When you use keyword arguments in a function call, the caller identifies the arguments by the parameter name.</p></div>

**Example:** https://replit.com/@ErAmbikaM/KeywordArguments#main.py

**_Default Arguments_**
* <p><div align="justify">A default argument is an argument that assumes a default value if a value is not provided in the function call for that argument. </p></div>

**Example:** https://replit.com/@ErAmbikaM/Default-Arguments#main.py

**_Variable Length Arguments_**
* <p><div align="justify">You may need to process a function for more arguments than you specified while defining the function. </p></div>
* <p><div align="justify">These arguments are called variable-length arguments and are not named in the function definition, unlike required and default arguments. </p></div>

**Syntax**

```python
def functionname([formal_args,] *var_args_tuple ):
   "function_docstring"
   function_suite
   return [expression]
```
**Example:** https://replit.com/@ErAmbikaM/Variablelengtharguments#main.py
### Algorithm:

What is algorithm? <
>
In mathematics and computer science, an algorithm  is a self-contained sequence of actions to be performed. 
Algorithm can also be defined a set of rules that precisely defines a sequence of operations.
Algorithms can perform calculation, data processing and automated reasoning tasks.

Real Life Example
Procedure to cook Bread Toast
Step 1 : Grab a loaf of bread
Step 2 : Get a pan and place it on the stove let it heat
Step 3 : Pour some oil on the pan and wait for oil to be heated
Step 4 : Put a slice on the pan and roast until it become brown in shade
Step 5 : Turn the slice and roast until it become brown in shade
Step 5 : Get the toasted bread from the pan and serve it on a plate with anything or nothing. 

The above procedure that explains “how to make a bread toast” and what are all the requirements before we start the procedures. We can code this procedure or algorithm in any programing language of your choice and simulate as results on the computer display. Else we can feed this procedure to the robot with proper instructions and we make the robot to do the bread toast for us. 

Example :
Algorithm for adding two numbers:
Step 1 : Get the 2 numbers from the user as input.
Step 2 : Perform addition of those 2 numbers.
Step 3 : Store the answer for display.
Step 4 : Display the stored value to the user.
Why We need Algorithm

Three reasons for using algorithms are efficiency, abstraction and reusability.

Efficiency: Certain types of problems, like sorting, occur often in computing. Efficient algorithms must be used to solve such problems considering the time and cost factor involved in each algorithm.

Abstraction: Algorithms provide a level of abstraction in solving problems because many seemingly complicated problems can be distilled into simpler ones for which well known algorithms exist. Once we see a more complicated problem in a simpler light, we can think of the simpler problem as just an abstraction of the more complicated one. For example, imagine trying to find the shortest way to route a packet between two gateways in an internet. Once we realize that this problem is just a variation of the more general shortest path problem, we can solve it using the generalised approach.

Reusability: Algorithms are often reusable in many different situations. Since many well-known algorithms are the generalizations of more complicated ones, and since many complicated problems can be distilled into simpler ones, an efficient means of solving certain simpler problems potentially lets us solve many complicated problems. 


Building Blocks of Algorithm
Computer is not smart as we humans. It requires a much more than single instruction to do any task. We can express our needs to computer using the algorithms. Algorithms includes basic building blocks, That is used to express any kind of the task to the computer.

Building Blocks of Algorithms are,
1.	Instructions/ Statements
2.	State
3.	Control Flow
4.	Functions

Instructions/ Statements

	In computer programming, a statement is the smallest standalone element of an imperative programming language that expresses some action to be carried out. It is an instruction written in a high-level language that commands the computer to perform a specified action.
There are two types of statement,
●	Simple Statement
●	Compound Statement

Simple Statements

It is used to represent single action need to be done.

●	assertion: assert(ptr != NULL);
○	Comparison
●	assignment: A:= A + 5
○	Assigning a value 5 to A
●	goto: goto next;
○	Sent the control to different block of same program
●	return: return 5;
○	Return a value 5 after the execution of function
●	call: CLEARSCREEN()
○	Calling the Function (ClearScreen) which performs clearing previous outputs from the computer screen






Compound Statement

It is a set of statements, that used to perform a sequence of operations repeatedly or condition based executions.

●	block: begin integer NUMBER; WRITE('Number? '); READLN(NUMBER); A:= A*NUMBER end
○	Set of statements
●	do-loop: do { computation(&i); } while (i < 10);
○	Looping a set of statements repeatedly until some condition is satisfied. We can’t predict when the condition become satisfiable. At least it will do the loop sequence once.
●	for-loop: for A:=1 to 10 do WRITELN(A) end
○	Looping a set of statements repeatedly until some condition is satisfied. We can run the loop for certain iterations. Prediction of loop termination is possible. 
●	if-statement: if A > 3 then WRITELN(A) else WRITELN("NOT YET"); end
○	Normally it contains two sets of statements. State or value is compared with a conditions if it is satisfied the “if” block will be executed otherwise else part will be executed.
●	switch-statement: switch (c) { case 'a': alert(); break; case 'q': quit(); break; }
○	It contains more than two blocks of statement each one has the conditions. When a program reaches a state with a value.  First hit of matching conditions block will be executed. If nothing matches then default block of statements will be executed
●	while-loop: while NOT EOF DO begin READLN end
○	Looping a set of statements repeatedly until some condition is satisfied. We can’t predict when the condition become satisfiable. This is loop is entry controlled. Control will enter into the loop only if condition is satisfiable. 


State:

	In information technology and computer science, a program is described as stateful if it is designed to remember preceding events or user interactions; the remembered information is called the state of the system.
If a program gets sufficient datas processed then it moves to another state. A successful execution of program include the reaching the  final state of the program.





Control Flow

In computer science, control flow (or flow of control) is the order in which individual statements, instructions or function calls of an imperative program are executed or evaluated. 

Control Flow Statement
Within an imperative programming language, a control flow statement is a statement which execution results in a choice being made as to which of two or more paths to follow.

Control Flow Statement Categories
 
●	Continuation at a different statement (unconditional branch or jump)
●	Executing a set of statements only if some condition is met (choice - i.e., conditional branch)
●	Executing a set of statements zero or more times, until some condition is met (i.e., loop - the same as conditional branch)
●	Executing a set of distant statements, after which the flow of control usually returns (subroutines, coroutines, and continuations)
●	Stopping the program, preventing any further execution (unconditional halt)

Primitive Control Statements

●	Labels
A label is an explicit name or number assigned to a fixed position within the source code, and which may be referenced by control flow statements appearing elsewhere in the source code. A label marks a position within source code, and has no other effect.

Eg:
LET X = 3
PRINT X

●	Goto
The goto statement (a combination of the English words go and to, and pronounced accordingly) is the most basic form of unconditional transfer of control.
Eg:
goto label

●	Subroutines
A piece of code was written once and then used many times from various other places in a program. The terminology for subroutines varies; they may alternatively be known as routines, procedures, functions (especially if they return results) or methods (especially if they belong to classes or type classes).

●	Sequence
In structured programming, the ordered sequencing of successive commands is considered one of the basic control structures, which is used as a building block for programs alongside iteration, recursion and choice.

●	Other Control Flow Statements

○	Choice
■	If-then-(else) statements
■	Case and switch statements
○	Loops
■	Count-controlled loops
■	Condition-controlled loops
■	Collection-controlled loops

Functions

module A small component of a computer program that may contain several routines. parameter In computer programming, a parameter is a value that is passed into a function or procedure. procedure A section of computer code that performs a specific task.

Functions "Encapsulate" a task (they combine many instructions into a single line of code). Most programming languages provide many built in functions that would otherwise require many steps to accomplish, for example computing the square root of a number. In general, we don't care how a function does what it does, only that it "does it"!

When a function is "called" the program "leaves" the current section of code and begins to execute the first line inside the function. Thus the function "flow of control" is:

1.	The program comes to a line of code containing a "function call".
2.	The program enters the function (starts at the first line in the function code).
3.	All instructions inside of the function are executed from top to bottom.
4.	The program leaves the function and goes back to where it started from.
5.	Any data computed and RETURNED by the function is used in place of the function in the original line of code.

Why do we Write Functions?

1.	They allow us to conceive of our program as a bunch of sub-steps. (Each sub-step can be its own function. When any program seems too hard, just break the overall program into sub-steps!)
2.	They allow us to reuse code instead of rewriting it.
3.	Functions allow us to keep our variable namespace clean (local variables only "live" as long as the function does). In other words, function_1 can use a variable called i, and function_2 can also use a variable called i and there is no confusion. Each variable i only exists when the computer is executing the given function.
4.	Functions allow us to test small parts of our program in isolation from the rest. This is especially true in interpreted languages, such as Matlab, but can be useful in C, Java, ActionScript, etc.

Steps to Writing a Function

1.	Understand the purpose of the function.
2.	Define the data that comes into the function from the caller (in the form of parameters)!
3.	Define what data variables are needed inside the function to accomplish its goal.
4.	Decide on the set of steps that the program will use to accomplish this goal. (The Algorithm)

Types of Functions

●	Parameterised Functions
○	This a functions that receives input while calling. It may or may not return any value to the caller.

●	Non-Parameterised Function 
○	This a functions does not receive any input while calling. It may or may not return any value to the caller.

Notation of algorithm

Algorithms are basically a set of instructions that, if correct and if followed carefully, produce some desired result. Since they are sets of instructions, they are generally presented in such a way that that the step-by-step nature of how they should be followed is readily apparent. The two most common representations are pseudocode and flowcharts.

Algorithms can be thought of as the recipe for taking the general solution for a class of problem and applying it to a specific instance of a problem covered by that class. For instance, the class of problem might be to find the surface area of a sphere given its radius. Through some problem solving means - perhaps by performing the fundamental calculus computation or perhaps simply by looking up the equation in a math book - we determine that the general solution to the problem is that the area is four times pi times the square of the radius. We can then use this general solution and create an algorithm that permits use to compute the surface area of a specific sphere:

TASK: Compute the surface area of a sphere
GET: radius
SET: area = 4pi*radius*radius


Pseudocode
Pseudocode is an artificial and informal language that helps programmers develop algorithms. Pseudocode is a "text-based" detail (algorithmic) design tool.

The rules of Pseudocode are reasonably straightforward. All statements showing "dependency" are to be indented. These include while, do, for, if, switch. Examples below will illustrate this notion.


Rules for Pseudocode Writing


1.	For looping and selection, The keywords that are to be used include Do While...EndDo; Do Until...EndDo; Case...EndCase; If...Endif; Call ... with (parameters); Call; Return ....; Return; When; Always use scope terminators for loops and iteration.
2.	As verbs, use the words Generate, Compute, Process, etc. Words such as set, reset, increment, compute, calculate, add, sum, multiply, ... print, display, input, output, edit, test , etc. with careful indentation tend to foster desirable pseudocode.
3.	Do not include data declarations in your pseudocode.

Examples:

For finding the given number is odd or even:

Input any number
Compute modulo for that  number
	If modulo value equals to zero
		Print “The number is Even”
	Else
		Print “The number is Odd”
End

To analyze the academic performance of the student

initialize passes to zero
initialize failures to zero
initialize student to one
while student counter is less than or equal to ten
input the next exam result
if the student passed
add one to passes
Else
add one to failures
add one to student counter
print the number of passes
print the number of failures
if eight or more students passed
print "raise tuition"

A Recommended Pseudocode Format
To aid in communication - particularly between you and the grader (the value of which should be relatively obvious) it is recommended that the problem be decomposed into a set of hierarchical tasks. The lowest-level tasks should either be tasks that are very straightforward to implement directly in C (using your level of knowledge) or the specific instructions for performing the task should be provided. By beginning each line with one of the keywords discussed below, the chance for miscommunication between you and the grader is greatly diminished.
Documentation Keywords
Documentation keywords describe what needs to be done or provides information about why something is being done. You will quickly discover that, if you have done a decent job of writing your pseudocode, that these lines make very useful comment lines in your final code.
●	TASK:
●	A TASK statement is something that the program must perform but that is described at a level more abstract than what can be coded directly. One way to think of it is that you break a problem down into a set of TASKs. Each TASK can, in turn, be broken down into more narrowly defined TASKs. At some point, the TASK can be described in terms of steps that can be directly implemented. From one perspective, anytime a TASK: keyword is used, it means that there should (or at least could) be a subordinate level of the hierarchy which is the pseudocode for that TASK. In practice, that pseudocode need not be present if the TASK is sufficiently narrow that the person implementing it can go directly from the TASK description to the actual code without the benefit of the detailed steps.
●	 
●	REM:
●	A REM statement is merely a remark or comment. They are useful if the TASK statement proves to be insufficient to convey all the desired information or if the reason that something is done or why it works is not obvious..
Action Keywords
Action keywords are the lines that actually do the work. There are three basic actions that can be carried out: changing the value stored at some location in memory, getting input from some device, or generating output to some device. We will use the SET, GET, and PUT keywords for these actions respectively.
●	SET:
This is an "action" keyword that denotes performing some operation that changes a value in memory. The most common example would be the evaluation of some equation.
●	PUT:
This is an "action" keyword that denotes an output operation, generally to the screen. If the destination is anything other than the screen, such as a file or the serial port, then that should be explicitly stated. 
●	GET:
This is an "action" keyword that denotes in input operation, generally from the keyboard. It is generally understood that there is an implied SET action involved where the value brought in gets stored in some memory location. If the source is anything other than the keyboard, such as a file or the serial port, then that should be explicitly stated.
Flow Control Keywords
While the action keywords perform the actual work, they are insufficient in and of themselves to write all but the most trivial programs. Of the three structured programming constructs, the action keywords are only sufficient to implement the first of them, namely a sequence of instructions. A program's true power comes from the other two - selection and repetition - because they give it the ability to select whether a particular action will actually be carried out based on the information made available to it at the time that it is executed. This ability is the result of controlling the flow of the program which is the purpose of the flow control keywords.
Because flow control is a more complex task that merely executing a single statement, all but the simplest flow control keywords are used in groups and there are some options in how to use them depending on the specific situation.
Selection - Case 1
●	SEL: (test condition)
○	TRUE:
■	Statement(s) to be executed if test condition is TRUE
○	FALSE
■	Statement(s) to be executed if test condition is FALSE
Selection - Case 2
●	IF: (test condition)
○	Statement(s) to be executed if test condition is TRUE
●	ELSE:
○	Statement(s) to be executed if test condition is FALSE
The advantage of Case 1 is that it clearly identifies the block as a selection construct, but it is a bit more involved than is usually necessary. The format of Case 2 is very close to the format of the actual C code that would result and is therefore a bit more straightforward to convert in the coding process, but not enough so as to be a significant factor.

In a legal outline, the ELSE: statement in Case 2 would be numbered one more than the IF: statement - in other words, if the IF: statement was numbered 3.4.2.6) then the ELSE: statement would be numbered 3.4.2.7). This can be useful or confusing depending upon how you think of it. If you think of the test condition controlling a single selection construct, then it would be nice if the controlling expression was one level in the outline and everything it controls was at a lower level. So this could be a bit confusing. However, this format actually emphasizes the fact that, in C, an "else" statement truly is a separate statement and that it must immediately follow an "if" statement that is at the same level of control. Neither convention is significantly better than the other - and you should quickly get comfortable with whichever you choose to use.
Repetition - Case 1
●	LOOP:
○	WHILE: (test condition)
○	Statement(s) to be executed if test condition is TRUE
Repetition - Case 2
●	LOOP:
○	Statement(s) to be executed if test condition is TRUE
○	WHILE: (test condition)
These two cases map directly into the while() and do/while() looping constructs of the C language. In Case 1, the test condition is evaluated prior to making the first pass through the statements controlled by it and, as a result, the possibility exists that those statements won't be executed even once. The only difference in Case 2 is that the statements controlled by the test condition are executed one time and the test is evaluated after that first pass. If the test condition is TRUE then another pass is made - and the test condition evaluated at the end of that and each succeeding pass until the test finally fails.
While the two cases above are more than adequate to represent any looping logic - in fact, either one of them by itself is sufficient, just more cumbersome in some cases - the logic is sometime clearer to the reader if it is expressed in terms of repeating the loop until some some condition is met - meaning that the loop is terminated as soon as the test condition becomes TRUE. 
Repetition - Case 3
●	LOOP:
○	UNTIL: (test condition)
○	Statement(s) to be executed if test condition is FALSE
Repetition - Case 4
●	LOOP:
○	Statement(s) to be executed if test condition is FALSE
○	UNTIL: (test condition)
Although C does not support a "loop until" construct (some languages do) converting Case 3 to an equivalent form of Case 1 is trivial - you simply invert the test condition. Similarly, Case 4 can be converted to Case 2 by the same mechanism.
Just as the selection construct can be streamlined, so too can a couple of the repetition constructs.
Repetition - Case 5 (streamlined version of Case 1)
●	WHILE: (test condition)
○	Statement(s) to be executed if test condition is TRUE
Repetition - Case 6 (streamlined version of Case 3)
●	UNTIL: (test condition)
○	Statement(s) to be executed if test condition is FALSE
Streamlining the other two is more difficult because, since the test comes at the end of the statement within the loop, it is very useful to mark the beginning of those statements in such a way that the fact that it is a loop is readily apparent to the reader. The LOOP: statement does that about as well as any other option would.
As you code loops, you will discover that it is frequently the case that there are steps that are logically associated with the loop but which must reside outside of the loop code. The most common by far is the need to initialize certain variables, especially counters, prior to entering the loop. Much less frequently, it is necessary to perform some cleanup tasks immediately after the loop is exited. A pseudocode construct that gathers all of these together so that their association is obvious is the following:
Repetition - Case 7
●	REP:
○	PRE:
■	Statement(s) to be executed prior to entering loop
○	WHILE: (test condition)
■	Statement(s) to be executed if test condition is TRUE
○	LOOP:
○	POST:
■	Statement(s) to be executed prior after the loop is finished
The above can be easily altered so as to cover all four of the first four cases. As shown, it implements Case 1. By switching the WHILE: and LOOP: statements it implements Case 2. Similarly, Case 3 is obtained simply by changing the WHILE: to UNTIL: and swapping the UNTIL: with the LOOP: then generated Case 4.


Examples
Pseudo Code for Sum of two numbers:

TASK : Sum of two numbers
READ num1
READ num2
Compute SUM:
Sum = num1 + num2
EndSUM
DISPLAY Sum
End
EndTASK

Pseudocode to find given number is odd or even

TASK: Find Odd or Even:
READ number
Compute MODULO:
Mod = number % 2;
 EndMODULO
	
	IF Mod = 0:
		PRINT “Number is Even”
	ELSE:
		PRINT “Number is Odd”
	EndTASK
Pseudocode to find factorial of given number

TASK: Finding Factorial of a number
READ number
Initialize Fact to 0 and CurrentVal to number

WHILE CurrentVal is not 1:
IF CurretVal >= 1:
	Fact = Fact * CurrentVal
	CurretVal = CurretVal - 1
EndIF
Else
	Print Fact
EndWHILE
End
EndTASK.
Flowcharts
Flowcharts are a graphical means of representing an algorithm, as should be expected, they have advantages and disadvantages compared to pseudocode. One of their primary advantages is that they permit the structure of a program to be easily visualized - even if all the text were to be removed. The human brain is very good at picking out these patterns and keeping them "in the back of the mind" as a reference frame for viewing the code as it develops. 

Most programmers also find it easier to sketch flowcharts on a piece of paper and to modify them by crossing out connection arrows and drawing new ones that they would working with pseudocode by hand. By the same token, most programmers do not like to develop flowcharts in an electronic format because the overhead of creating and modifying it is generally more than they want to deal with while pseudocode lends itself to such electronic development. 

Furthermore, if the pseudocode is already in an electronic format that has been structured to lend itself to translation to the final language - such as the one recommended in the previous section - then doing so can be a very simply matter of copying the pseudocode to a new file, overlaying the necessary syntax associated with the language, and compiling the result. This can be a powerful advantage of pseudocode over flowcharts where the entire source code still has to be typed by hand unless you are fortunate to have a tool that can take a flowchart - typically developed using that same tool - and translating it to directly to code. Such tools do exist - and they tend to be rather expensive.

Now that we have looked as some of the pros and cons of flowcharts relative to pseudo code, let's delve into flowcharting itself. The idea behind a flowchart is that it links together a series of blocks each of which perform some specific task. Each of these tasks is represented by a block and has exactly one arrow leading to it and, more importantly, one arrow exiting from it. This is key to the concept of a "structured program". 

The shape of the block may convey additional information about what is happening. For instance, a rectangular block is frequently used to indicated that a computation is occurring while a slanted parallelogram is used to indicate some type of input or output operation. The diversity of shapes that can be used and what they mean is staggering - for instance a different shape can be used to indicated output to a tape drive versus to a hard disk or to indicate output in text format verses binary format. By using such highly specialized symbols, much of what is happening can be conveyed by the symbols themselves. But the power of using these distinctions is generally only useful to people that work with flowcharts continuously, professionally, and who are describing very large and complex systems. At our level, it is far better to restrict ourselves to a minimum number of shapes and explicitly indicate any information that otherwise might have been implied by using a different shape.

Circle - Entry/Exit Point

The circle indicates the entry and exit point for the program - or for the current segment of the program. The entry point has exactly one arrow leaving it and the exit point has exactly one arrow entering it. Execution of the program - or of that segment of the program - always starts at the entry point and finishes at the exit point.

  
Rectangle - Task

The rectangle represents a task that is to be performed. That task might be as simple as incrementing the value of a single variable or as complex as you can imagine. The key point is that it also has a single entry point and a single exit point. 

 


Parallelogram - Input/Output

The parallelogram is used to indicate that some form in input/output operation is occurring. They must also obey the single entry single exit point rule which makes sense given that they are a task-block except with a slightly different shape for the symbol. We could easily eliminate this symbol and use the basic rectangle but the points at which I/O occur within our programs are extremely important and being able to easily and quickly identify them is valuable enough to warrant dealing with a special symbol.

Since a Task block can be arbitrarily complex, it can also contain I/O elements. Whether to use a rectangle or a parallelogram is therefore a judgment call. One way to handle this is to decide whether a task's primary purpose is to perform I/O. Again, that is a judgment call. Another option is to use a symbol that is rectangular on one side and slanted on the other indicating that it is performing both I/O and non-I/O tasks.  

 

Diamond - Decision Point

The diamond represents a decision point within our program. A question is asked and depending on the resulting answer, different paths are taken. Therefore a diamond has a single entry point but more than one exit point. Usually, there are two exit points - one that is taken if the answer to the question is "true" and another that is taken if the answer to the question is "false". This is sufficient to represent any type of branching logic including both the typical selection statements and the typical repetition statements. However, most languages support some type of "switch" or "case" statement that allows the program to select one from among a potentially large set of possible paths. The basic two-exit-point diamond is fully capable of representing this construct, but it is generally cleaner and more useful to represent it using a as many exit points from the diamond as there are paths.

 

Arrow - Interblock Flow

The arrows simply show which symbol gets executed next. The rule is that once an arrow leaves a symbol, it must lead directly to exactly one other symbol - arrows can never fork and diverge. They can, however, converge and join arrows coming from other blocks.
 








Sum of two numbers flow chart

 



















Finding number is even or odd
 

Program to Find a factorial of the given number

 


programming language notation

A programming language is a formal language that specifies a set of instructions that can be used to produce various kinds of output. Programming languages generally consist of instructions for a computer. Programming languages can be used to create programs that implement specific algorithms.

Eg : C, C++, COBAL, JAVA, Python ... etc  

Programing language consist of syntax and semantics to processed by the compiler or interpreter we must represent our logic with proper notations otherwise the program won’t work at all. 

Let’s take a python program to compute sum of two numbers,
num1 = input('Enter first number: ')
num2 = input('Enter second number: ')
# Add two numbers3
sum = int(num1) + int(num2)
# Display the sum
print(sum)
Let’s take a C program to compute sum of two numbers,
#include<stdio.h>
int main(){
Int num1, int num2, sum;
printf (Enter first number:”);
scanf(“%d”,&num1);
printf (Enter second number:”);
scanf(“%d”,&num2);
sum = num1 + num2;
printf(“%d”, sum)
return 0;
}

Let’s take a Java program to compute sum of two numbers,

class Main{
public static void main(String[] args){
int num1, num2, sum;
Scanner in = new Scanner(System.in);
System.out.println(“Enter first number:”);
num1 = in.nextInt();
System.out.println(“Enter second number:”);
num2 = in.nextInt();
sum = num1 + num2;
System.out.println(sum);
}
}

Above that we have 3 styles of the programming with 3 different language but achieves the same logic.

The programmes different only by syntax and rules 

Python
●	It is dynamic type no declaration of variable needed.
●	Just do and display.
●	It is based on Dynamic OOPS .
C 
●	It is structure oriented we need to declare a variable before we use it.
●	Anything that represented as block of codes and do the work.
●	It is procedure oriented structured language.
JAVA
●	It is object oriented derived from C and C++
●	Coding style is inherited from C and C++ for easy transformation.
●	Everything is considered as objects and depends on dynamic memory allocations.

Problem solving with algorithms

Problem solving can be achieved so many ways, If you need to done with computers then you must design algorithm and then you must implement algorithm with any of your programming language choice.

Algorithms with iteration:

In computational mathematics, an iterative method is a mathematical procedure that generates a sequence of improving approximate solutions for a class of problems, in which the n-th approximation is derived from the previous ones. A specific implementation of an iterative method, including the termination criteria, is an algorithm of the iterative method. An iterative method is called convergent if the corresponding sequence converges for given initial approximations. 

For Example To find power of a number

Step 1: Get a base number
Step 2: Get a power
Step 3: Initialize result value with number and pow with power
Step 4: Start with pow as 1
Step 5: Multiply result and number then increase pow by one
Step 6: Repeat Step 5 Until pow reaches value of power
Step 7: Break the loop and display the result
Step 8: End

In pseudocode:

TASK: To Find Power of a number
READ number
READ Power
Initialize result with number and pow with Power
WHILE pow < Power:
result = result * number
Increase pow by 1
End Loop
PRINT result
End

Recursive Algorithm

A recursive algorithm is an algorithm which calls itself with "smaller (or simpler)" input values, and which obtains the result for the current input by applying simple operations to the returned value for the smaller (or simpler) input. More generally if a problem can be solved utilizing solutions to smaller versions of the same problem, and the smaller versions reduce to easily solvable cases, then one can use a recursive algorithm to solve that problem. For example, the elements of a recursively defined set, or the value of a recursively defined function can be obtained by a recursive algorithm. 

If a set or a function is defined recursively, then a recursive algorithm to compute its members or values mirrors the definition. Initial steps of the recursive algorithm correspond to the basis clause of the recursive definition and they identify the basis elements. They are then followed by steps corresponding to the inductive clause, which reduce the computation for an element of one generation to that of elements of the immediately preceding generation. 

In general, recursive computer programs require more memory and computation compared with iterative algorithms, but they are simpler and for many cases a natural way of thinking about the problem. 


For Example To find power of a number

Step 1: Get a base number
Step 2: Get a power
Step 3: Send a number and power to routine 
Step 4: In routine Compare power with 1 
	Step 5: If it is equal to 1 then return number
	Step 6: Else Compute the same routine (Step 4 and 5) with a same number and      reduced power by 1  
Step 7: display the result
Step 8: End

In pseudocode:

TASK: To Find Power of a number
READ number
READ Power
result = FIND_POWER number and power
FIND_POWER number and power:
	IF power = 1:
		RETURN number
	ELSE
		result = FIND_POWER number and power -1
RETRUN result
EndFIND_POWER

PRINT result
End
EndTASK

