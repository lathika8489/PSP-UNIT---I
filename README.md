# **<center> GE8151 PROBLEM SOLVING AND PYTHON PROGRAMMING </center>**
## <center>**UNIT I ALGORITHMIC PROBLEM SOLVING**</center>
<div align="justify"><p><i>Algorithms - building blocks of algorithms (instruction/statements, state, control flow, functions) - notation (pseudo code, flowchart, programming language) </b> algorithmic problem solving, simple strategies for developing algorithms (iteration, recursion)
</div></p></i>
<p><div align="justify"><b><i>Illustrative programs: find minimum in a list, insert a card in a list of sorted cards, guess an integer number in a range, Towers of Hanoi.</b></i></p>

https://www.memcode.com/courses/2283 - 20+ flashcards to review the contents of this unit.# UNIT - 1

>## **Table of Contents**
***
1.1. Algorithms

1.2. Building blocks of Algorithms 
   - Statements
   - State
   - Control flow
   - Functions
     
1.3. Notation
   - Pseudocode
   - Flow Chart
   - Programming Language
     
1.4. Algorithmic Problem Solving
     
1.5. Simple strategies for developing Algorithms
     - Iteration
     - Recursion

1.6. Illustrative problems
   - Find minimum in a list
   - Insert a card in a list of sorted cards
   - Guess an integer number in a range
   - Towers of Hanoi
   
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
<p><div align="justify">&nbsp Algorithm is a well-defined computational procedure consisting of instructions that takes some value or set of values as input and produces some values or set of values as output.</div></p>

**Example :**<br/>
Algorithm for adding two numbers:
```
Step 1 : Get the 2 numbers from the user as input.
Step 2 : Perform addition of those 2 numbers.
Step 3 : Store the answer for display.
Step 4 : Display the stored value to the user.
```
### Why We need Algorithm?
Three reasons for using algorithms are efficiency, abstraction and reusability.
- **Efficiency**: Certain types of problems, like sorting, occur often in computing. Efficient algorithms must be used to solve such problems considering the time and cost factor involved in each algorithm.
- **Abstraction**: Algorithms provide a level of abstraction in solving problems because many seemingly complicated problems can be distilled into simpler ones for which well known algorithms exist. Once we see a more complicated problem in a simpler light, we can think of the simpler problem as just an abstraction of the more complicated one. For example, imagine trying to find the shortest way to route a packet between two gateways in an internet. Once we realize that this problem is just a variation of the more general shortest path problem, we can solve it using the generalised approach.
- **Reusability**: Algorithms are often reusable in many different situations. Since many well-known algorithms are the generalizations of more complicated ones, and since many complicated problems can be distilled into simpler ones, an efficient means of solving certain simpler problems potentially lets us solve many complicated problems. 

### Qualities of an Algorithm
- **Accuracy**: Algorithm should provide accurate result
- **Memory**: It should require minimum computer memory
- **Time**: It should take finite amount of time.
- **Sequence**: The procedure of an algorithm must be in sequential form

### Characteristics/Properties of Algorithm
**Input**: All the algorithms should have some input. The logic of the algorithm should work on this input to give the desired result.<br />
**Finiteness**: An algorithm must always terminate after a finite number of steps.<br />
**Definiteness**: Every step of the algorithm should be clear and not any ambiguity.<br />
**Effectiveness**: Every step in the algorithm should be easy to understand and can be implemented using any programming language.<br />
**Output**: At least one output should be produced from the algorithm based on the input given.<br />

### Advantage
- It is a stepwise description of a solution, which makes easy to understand.
- It is not dependent on any programming language.
- It is easier for programmer to convert into an actual program.

### Disadvantage
- It is difficult to show branching and looping statements.
- It is time consuming, algorithm needs to be developed first which is then converted to program.


>## **Building Blocks**
<p><div align="justify">&nbsp&nbsp An Algorithm is an effective method that can be expressed within a finite amount of space and time and in a well-defined formal language for calculating a <i><b>function</b></i>. Starting from an initial <i><b>State</b></i> and initial input, the <i><b>Instructions</b></i> decribe a computation that, when executed, proceeds through a finite number of well-defined sucessive states, eventually producing "output" and terminating at final ending stage. An <i><b>Instruction</b></i> is a single operation, that describes a computation. When it is executed it is converted from one state to other. The<i><b> State </b></i> of an algorithm is defined as its condition regarding stored data.The state shows its current values or contents.<b><i> Control flow </b></i> is the order in which individual statements, instructions or function calls of an algorithm are executed or evaluated. For Complex problems our goal is divide the task into smaller and simpler functions during algorithm design. So a set of related sequence os steps, part of a larger algorithm is known as <b><i>functions.</i></b></div></p>
<p><div align="justify">&nbsp&nbsp We can express our needs to computer using the algorithms. Algorithms includes basic building blocks, That is used to express any kind of the task to the computer.
<p><div align="justify">Building Blocks of Algorithms are,<br/>
1. Instructions/ Statements<br/>
2. State<br/>
3. Control Flow<br/>
4. Functions. </p></div>

### Statements:
 
Statement is a single action in a computer.
 
In a computer statements might include some of the following actions
   input data-information given to the program
   process data-perform operation on a given input
   output data-processed result
 
**State:**
Transition from one process to another process under specified condition with in a time is called state.
 
**Control flow:**
The process of executing the individual statements in a given order is called control flow.
The control can be executed in three ways
1. Sequence
2. Selection
3. Iteration
 
**Sequence:**
Sequential control means that the steps of an algorithm are carried out in a sequential manner, where each step is executed exactly once.
 
```
Example: Algorithm to convert Centigrade to Fahrenheit

Step 1: Read the temperature in degree Centigrade
Step 2: Convert the Centigrade to Fahrenheit using the formula
			F= 9/5 * c+32
Step 3: Print the Celsius and Fahrenheit value
```
```
Example: Add two numbers:
Step 1: Start
Step 2: get a,b
Step 3: calculate c=a+b
Step 4: Display c
Step 5: Stop
```
**Selection:**
A selection statement causes the program control to be transferred to a specific part of the program based upon the condition.
If the conditional test is true, one part of the program will be executed, otherwise it will execute the other part of the program.
Algorithms can use selection to determine a different set of steps to execute based on a Boolean expression.If the conditional test is true, one part of the algorithm will be executed, otherwise it will execute the other part of the algorithm.

```
# Example: Algorithm to find Greatest of two numbers

Step 1: Read first numbers A
Step 2: Read second number B
Step 3: IF(A>B) then 
			Print A is big
		Else 
			Print B is big
```
  
Example: Write an algorithm to check whether he is eligible to vote or not
Step 1: Start
Step 2: Get age
Step 3: if age >= 18 print “Eligible to vote”
Step 4: else print “Not eligible to vote”
Step 6: Stop
 
**Iteration:**
In some programs, certain set of statements are executed again and again based upon conditional test. i.e. executed more than one time. This type of execution is called looping or iteration.
Algorithms often use repetition to execute steps a certain number of times or until a certain condition is met.


```
Example: Print 'Hello world' 5 times

Step 1 : Start
Step 2 : Initialize the value of i as 1
Step 3 : Check the condition i less than or equal to 5, if the condition is true goto step 3.1 else goto step 4
         Step 3.1: Print “Hello World” and increment 
         	         the value of i by 1
         Step 3.2: Repeat the Step 3 until the condition is true
Step 4 : Stop

```
 
Example : Write an algorithm to print all natural numbers up to n

Step 1: Start
Step 2: get n value.
Step 3: initialize i=1
Step 4: if (i<=n) go to step 5 else go to step 7
Step 5: Print i value and increment i value by 1
Step 6: go to step 4
Step 7: Stop
 
**Functions:**
Function is a sub program which consists of block of code(set of instructions) that performs a particular task.
For complex problems, the problem is been divided into smaller and simpler tasks during algorithm design.
 
#### Benefits of Using Functions
1. Reduction in line of code
2. Code reuse
3. Better readability
4. Information hiding
5. Easy to debug and test
6. Improved maintainability

``` 
Example: Algorithm for addition of two numbers using function

Main function()
Step 1: Start
Step 2: Call the function add()
Step 3: Stop
 
sub function add()
Step 1: Function start
Step 2: Get a, b Values
Step 3: add c=a+b
Step 4: Print c
Step 5: Return
```
>## **Notations**
***
## **<u>Notation</u>**
<p><div align="justify">&nbsp There are different notation of representing an algorithms.<div></p>
	1. Pseudocode
	2. Flowchart
	3. Programming Language

### **Pseudocode
Pseudo code is an informal way of programming description that does not require any strict programming language syntax. It is an outline of a program written in a form that can be easily converted into real programming statements.

```
A pseudocode to add two numbers and display the results:
	
    READ num1,num2
	Result=num1+num2
	PRINT result.

```

## Basic Guidelines for Writing Pseudocode
- Statements should be written in English and programming language independent.
- Steps must be understandable and it should not be difficult
- Each instruction should be written in a separate line
- Keywords must be capitalized
- Each set of instruction must be written from top to bottom
- It should be easy for translating the design into code in any programming language.

## Advantages
- Pseudocode is language independent, it can be used by most of the programmers
- It becomes easy to develop a program.
- It is compact and easy to modify.

## Disadvantages
- It does not provide visual representation of the program logic.
- No standard rules for writing pseudocode.
- It is not used to understand the flow of the program control.

```
Example: Pseudo Code for Sum of two numbers:

TASK : Sum of two numbers
READ num1
READ num2
Compute SUM:
Sum = num1 + num2
EndSUM
DISPLAY Sum
End
EndTASK
```
```
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
```
```
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
```
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
		  
## **Illustrative Problems**
1. Find Minimum in the List
2. Insert a card in the list of sorted cards
3. Guess an integer in the range
4. Tower of Hanoi

		  
		  
# Problem Statement
**We will see  Python program to find the smallest number in a List.**
### For example
- If the list is [15, 20, 10, 16] then the program should display number 10 as the output (the smallest number in the given list).

## Python Code
~~~python
#find minimum of two numbers
# a and b are parameters''


def find_min(a, b):
    if a < b:
        return a
    return b


print("Enter two values :")
a = int(input())
b = int(input())
print("Minimum number is ", find_min(a, b))
~~~

~~~python
#find minimum of three numbers

def find_min(a, b):
    if a < b:
        return a
    return b

# a, b and c are parameters
def min_of_three(a, b, c):
    minVal = find_min(a, b)
    if c < minVal:
        return c
    return minVal


print("Enter three numbers: ")
a = int(input())
b = int(input())
c = int(input())

print("Minimum number is ", min_of_three(a, b, c))
~~~


~~~python
# find minimum of a list
def min_of_list(aList):
    if not aList:
        return None
    minVal = aList[0]
    for number in aList[1:]:
        if number < minVal:
            minVal = number
    return minVal


myList = []
limit = int(input("Enter the limit: "))
print("Enter the elements:\n")
for i in range(limit):
    element = int(input())
    myList.append(element)

print("Minimum of list is ", min_of_list(myList))
~~~
## Problem Statement

**Ramesh want to insert the new cards into the sorted cards**
* Insert a card must be in correct position

## Python Code

```python
order = {
    'A': 1, '2': 2, '3': 3, '4': 4,
    '5': 5, '6': 6, '7': 7, '8': 8,
    '9': 9, '10': 10,
    'J': 11, 'Q': 12, 'K': 13
}


def insertCard(deck, newCard):
    for card in deck:
        if order[card] > order[newCard]:
            index = deck.index(card)
            deck.insert(index, newCard)
            break
    return deck


deck = ['2', '5', '8', '10', 'J', 'K']  # initial set of cards
print("deck = ", deck)
newCard = input("Enter the new card to be inserted:")  # get the new card
insertCard(deck, newCard)
print(deck)

```
## Problem Statement

___
**Shankar and Vijay are playing a game of integers in which Shankar chooses an integer in his mind (can be any integer value with in range of 1 to 100 ) and Vijay had to find that integer through some guesses.**
___

_Shankar can provides 3 hints to Vijay ,each hint can be one of the below types:_
* Type 1 : Guess is Low
* Type 2 : Guess is High
* Type 3 : You guessed my number!

Now Vijay has to make some guesses in order to find Shankar's integer._
___

**Note:**  vijay is given only 10 chances to guess the number and if vijay wins the game then return true otherwise return false.


## Python Code
```python
"""Guess the Number Try to guess the secret number based on hints."""

import random

def ask_for_guess():
    '''returns an integer number as guessed by the user'''
    while True:
        guess = input('> ')  # Enter the guess.

        if guess.isdecimal():
            return int(guess)  # Convert string guess to an integer.
        print('Please enter a number between 1 and 100.')

print('*** Guess the Number ***')
print()
secretNumber = random.randint(1, 100)  # Select a random number.
print('I am thinking of a number between 1 and 100.')

for i in range(10):  # Give the player 10 guesses.
    print('You have {} guesses left. Take a guess.'.format(10 - i))

    guess = ask_for_guess()
    if guess == secretNumber:
        break  # Break out of the for loop if the guess is correct.

    # Offer a hint:
    if guess < secretNumber:
        print('Your guess is too low.')
    if guess > secretNumber:
        print('Your guess is too high.')

# Reveal the results:
if guess == secretNumber:
    print('Yay! You guessed my number!')
else:
    print('Game over. The number I was thinking of was', secretNumber)
```
## Problem Statement

**The mission is to move all the disks to some another tower without violating the sequence of arrangement.**
_A few rules to be followed for Tower of Hanoi are_

- Only one disk can be moved among the towers at any given time.
- Only the "top" disk can be removed.
- No large disk can sit over a small disk.

**Tower of Hanoi puzzle with n disks can be solved in minimum 2n−1 steps**

## Python Code

```python
# Tower of Hanoi

# one disk is tower A, destination is tower B, intermediate is tower C
print("Tower of Hanoi - with one disk")
source = 'A'
destination = 'B'
print("Move top disk from ", source, " to ", destination)
print()

# Two disk is at tower A, destination is tower B, intermediate in tower C
print("Tower of Hanoi - with 2 disk")
source = 'A'
destination = 'B'
temp = 'C'
print("Move top disk from ", source, " to ", temp)
print("Move top disk from ", source, " to ", destination)
print("Move top disk from ", temp, " to ", destination)
print()


# In a recursive way

def tower_of_hanoi(n, fromTower, toTower, tempTower):
    if n == 1:
        print("Move top disc from ", fromTower, " to ", toTower)
    else:
        # Move n-1 disks from source to temp
        tower_of_hanoi(n - 1, fromTower, tempTower, toTower)
        # Move top disk from source to destination
        print("Move top disc from ", fromTower, " to ", toTower)
        # Move n-1 disks from temp to the destination
        tower_of_hanoi(n - 1, tempTower, toTower, fromTower)


n = int(input("Enter number of disks:"))
tower_of_hanoi(n, 'A', 'B', 'C')

```
