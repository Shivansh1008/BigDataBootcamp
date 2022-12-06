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

Q26. What is a string? How can we declare string in Python?
Strings are used for storing text/characters.Python strings are "immutable" which means they cannot be changed after they are created.
a=("hello") in double or single inverted commas

Q27. How can we access the string using its index?
a=("hello")
print(a[2])

Q28. Write a code to get the desired output of the following
string = "Big Data iNeuron"
desired_output = "iNeuron"

a=("Big Data iNeuron")
b,c,d=a.split()
print(d)


Q29. Write a code to get the desired output of the following
string = "Big Data iNeuron"
desired_output = "norueNi"
a=("Big Data iNeuron")[::-1]
b,c,d=a.split()
print(b)


Q30. Resverse the string given in the above question.
a=("Big Data iNeuron")[::-1]
b,c,d=a.split()
print(b[::-1])

Q31. How can you delete entire string at once?
del string varible

Q32. What is escape sequence?
An escape sequence is a sequence of characters that, when used inside a character or string, does not represent itself but is converted into another character or series of characters. for eg \t \n , print('Who\'s this?')  Who's this?

Q33. How can you print the below string?  'iNeuron's Big Data Course'
print("'iNeuron's Big Data Course'")

Q34. What is a list in Python?
Lists are used to store multiple items in a single variable.

Q35. How can you create a list in Python?
list_example=["apple","mango","4","true"]

Q36. How can we access the elements in a list?
If we want to access 3 rd elemet from above list
3rd_elememt=list_example[2]

Q37. Write a code to access the word "iNeuron" from the given list.
lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
print(lst[4][2])

Q38. Take a list as an input from the user and find the length of the list.
a=[]
for i in input().split():
  a.append(i)
print(len(a))

Q39. Add the word "Big" in the 3rd index of the given list.
lst = ["Welcome", "to", "Data", "course"]

Q40. What is a tuple? How is it different from list?
Tuple is similar to list it also store values it is represented by () and another diffrence is it is immutable 

Q41. How can you create a tuple in Python?
Tupple_example=("apple","mango","4","true")

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.
no we can't add in the tupple as tupple is immutable 

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?
yes  a=("My" ,"name","is")
b=("shivansh","singh")
print(a+b) 
output = ('My', 'name', 'is', 'shivansh', 'singh')

Q44. Take a tuple as an input and print the count of elements in it.
a=[]
for i in input().split():
  a.append(i)
a=tuple(a)
print(a)
print(len(a))

Q45. What are sets in Python?
Sets are the store values the only diffrence it has with list that it contains only unique values

Q46. How can you create a set?
a={"delhi","pune","indore"}

Q47. Create a set and add "iNeuron" in your set.
a={"delhi","pune","indore"}
a.add("iNeuron")
print(a)


Q48. Try to add multiple values using add() function.

Q49. How is update() different from add()?

Q50. What is clear() in sets?

Q51. What is frozen set?

Q52. How is frozen set different from set?

Q53. What is union() in sets? Explain via code.

Q54. What is intersection() in sets? Explain via code.

Q55. What is dictionary ibn Python?

Q56. How is dictionary different from all other data structures.

Q57. How can we delare a dictionary in Python?

Q58. What will the output of the following?

var = {}
print(type(var))
Q59. How can we add an element in a dictionary?

Q60. Create a dictionary and access all the values in that dictionary.

Q61. Create a nested dictionary and access all the element in the inner dictionary.

Q62. What is the use of get() function?

Q63. What is the use of items() function?

Q64. What is the use of pop() function?

Q65. What is the use of popitems() function?

Q66. What is the use of keys() function?

Q67. What is the use of values() function?

Q68. What are loops in Python?

Q69. How many type of loop are there in Python?

Q70. What is the difference between for and while loops?

Q71. What is the use of continue statement?

Q72. What is the use of break statement?

Q73. What is the use of pass statement?

Q74. What is the use of range() function?

Q75. How can you loop over a dictionary?

Coding problems
Q76. Write a Python program to find the factorial of a given number.

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

Q79. Write a Python program to check if a number is prime or not.

Q80. Write a Python program to check Armstrong Number.

Q81. Write a Python program to find the n-th Fibonacci Number.

Q82. Write a Python program to interchange the first and last element in a list.

Q83. Write a Python program to swap two elements in a list.

Q84. Write a Python program to find N largest element from a list.

Q85. Write a Python program to find cumulative sum of a list.

Q86. Write a Python program to check if a string is palindrome or not.

Q87. Write a Python program to remove i'th element from a string.

Q88. Write a Python program to check if a substring is present in a given string.

Q89. Write a Python program to find words which are greater than given length k.

Q90. Write a Python program to extract unquire dictionary values.

Q91. Write a Python program to merge two dictionary.

Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]
Q94. Write a Python program to get all combinations of 2 tuples.

Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
Q95. Write a Python program to sort a list of tuples by second item.

Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
Q96. Write a python program to print below pattern.

* 
* * 
* * * 
* * * * 
* * * * * 
Q97. Write a python program to print below pattern.

    *
   **
  ***
 ****
*****
Q98. Write a python program to print below pattern.

    * 
   * * 
  * * * 
 * * * * 
* * * * * 
Q99. Write a python program to print below pattern.

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 
