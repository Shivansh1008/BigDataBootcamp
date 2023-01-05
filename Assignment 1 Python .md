Q1 Why do we call Python as a general purpose and high-level programming language?
A general- purpose programming language is a programming language designed to be used for building software, apps, projects in a wide variety of application domainmeans in computer software and high-level means it's easy for humans to understand.
Q2.Why is Python called a dynamically typed language?
 Dynamic typing means that the type of the variable is determined only during runtime.
Q3 List some pros and cons of Python programming language
PROS - 
It is Object-Oriented.
It has Lots of Libraries.
It has Built-in Data Structures.
It's Widely Applicable.
cons-
Poor Memory Efficiency. To make it simple for the developer, Python needs a lot of memory space; this can be a tad problematic if you want to develop apps where you need to optimize memory.
Slow Speed.
Weak in Mobile Computing.
Runtime Errors.
Q4  In what all domains can we use Python?
 artificial intelligence, machine learning and deep learning
Q5 What are variable and how can we declare them?
Variables are the basic unit of storage in a programming language. These variables consist of a data type, the variable name, and the value to be assigned to the variable. A variable declaration always contains two components: the type of the variable and its name.
a=int()

Q6 How can we take an input from the user in Python?
a=input()

Q7  What is the default datatype of the value that has been taken as an input using input() function?
String

Q8 What is type casting?
Converting one datatype into another

Q9 Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Yes we take using split function   for ex a,b=input().split()

Q10 What are keywords?
special reserved words that have specific meanings and purposes and can't be used for anything but those specific purposes for example for,in, while.

Q11  Can we use keywords as a variable? Support your answer with reason.
no,compliler won't be able to distinguish between keyword and variable 

q12 What is indentation? What's the use of indentaion in Python?
Indentation refers to the spaces at the beginning of a code line .Python uses indentation to indicate a block of code.

Q13 How can we throw some output in Python?
print("hello")

 Q14 What are operators in Python?
 perform operation n variable and values

Q15. What is difference between / and // operators?
/= division   14/3=4.66666
//= floor division   14/3=4

Q16. Write a code that gives following as an output.   iNeuroniNeuroniNeuroniNeuron
a=str("iNeuron")
x=a+a+a+a
print(x)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
x=int(input())
if x%2==0:
    print(x,"is an even number")
else:
    print(x,"is a odd number")

Q18. What are boolean operator?
There are three logical operators that are used to compare values. They evaluate expressions down to Boolean values, returning either True or False . These operators are and , or not.

Q19. What will the output of the following?
1 or 0 = 1
0 and 0 = 0
True and False and True = False 
1 or 0 or 0  = 1

Q20. What are conditional statements in Python?
is used to handle conditions in your program for eg if, else,elif

Q21. What is use of 'if', 'elif' and 'else' keywords?
All are condional statement

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
a=int(input("Tell me your age : "))
if a>=18:
    print("I can vote")
else:
    print("I can't vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.  numbers = [12, 75, 150, 180, 145, 525, 50]
numbers = [12, 75, 150, 180, 145, 525, 50]
sum=0
for a in numbers:
  if a%2==0:
    sum=sum +a
print(sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
a,b,c=input("enter 3 number: ").split()
if a>b:
  if a>c: 
    print(a,"is greatest value")
  else:
    print(c,"is greatest value")
else:
    if b>c: 
      print(b,"is greatest value")
    else:
      print(c,"is greatest value")

Q25. Write a program to display only those numbers from a list that satisfy the following conditions
The number must be divisible by five
If the number is greater than 150, then skip it and move to the next number
If the number is greater than 500, then stop the loop

numbers = [12, 75, 150, 180, 145, 525, 50]
req_list=[]
for x in numbers:
  if (x%5==0 and x<150):
    req_list.append(x)
  if (x>500):
    break
print(req_list)
