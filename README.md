# python
This repository is shall document my progress in learning Python concepts
#Python in job market
Python is a popular programming language that offers great job opportunities. Learning Python opens doors to various roles in the tech industry. 
To get a job, you may also need to learn other languages. This course covers the basics of Python and helps you get ready for the job market.
Python jobs can be in fields like working with databases, network programming, or becoming a software engineer or data analyst. 
Companies are switching to open-source software like Python, making it even more valuable. 
This course teaches you a lot in a short time and introduces you to a new way of writing code. So, if you're interested in tech careers, Python is a great place to start.

#History 
Python is a programming language created in the late 1980s by Guido van Rossum in the Netherlands. It's designed to be simple and reliable, and it comes with a handy library for many tasks that programs need to do. 
Python focuses on making it easy for programmers to write, read, and document their code. While some languages prioritize fast compilation, Python strikes a balance between speed and readability, making it easier for developers. 
Python is implemented in C, which means it can work on various operating systems like UNIX, Linux, Windows, and more. It was influenced by other languages like ABC and Modula-3.

#Comments in python
Comments are used in Python just as other programming languages. 
The purpose is the same; to add to the code useful descriptions on what is occurring for general documentation. 
They start with the # character and extend to the end of a line. For example: # this is a comment 
name = 'Metuso' #actually my surname

In the following declaration the # doesn't denote a character since it is within quotes
text = 'This character # is used to denote a comment'

Using python
The first exercise:
o = `This is how backslash character is displayed \n in python \n "\\"`
print(o)
The second exercise (write the word "python" using the * character): 
# the code is one print statement 
print("\n**** *   * ********* *   *  ****  *    *\n*  *  * *      *     *   * *    * * *  *\n****   *       *     ***** *    * *  * *\n*      *       *     *   * *    * *   **\n*      *       *     *   *  ****  *    *")

# Introduction to variables
Variables are foundational characteristic to any programming language. It is how data is stored in memory for retrival at a later stage such as when perfoming a calculation i.e a function.
Variables have the following rules associated with them: 
1) They cannot start with a number or contain spaces.
2) They are case sensitive so firstName != Firstname != FIRSTname these are all different variables
3) They cannot use the already built in method names i.e del, from, in, dir, upper etc.

# Using variables
Variables are automatically assigned to the apppropriate data type. 
For example: name = 'python' is automatically assigned to the string data type since it is in single quotes.

#Casting
Casting refers to changing the data type of a value. This is done when you want to use a value as a different type than it originally is. There are two ways to do this: implicit and explicit casting.
Implicit casting happens when the computer changing a value's data type won't lose any information. For example, if you have a whole number (integer) and you need to use it as a decimal number (floating-point), the computer can do this automatically without any extra instructions.
Explicit casting is when you need to give specific instructions to the computer. This is because the computer can't be sure about changing the data type, as it might lose some information. You write extra code to control how the value is converted from one type to another. For instance, if you want to turn a decimal number into a whole number, you need to provide detailed instructions to avoid losing the decimal part.

#Consolidating Learning
First exercise (write a program that will take the sum of 2 numbers and subtract 3 from the result)
suM = str('2 + 4 = 6')
sub = str('6 - 3 = 3')
print("The first number is: 2 \n The second number is 4 ")
print(suM)
print(sub)

n1 = 2
n2 = 4

Second exercise (use the previous exercise to add the totals together as characters not as numbers
suM =  n1 + n2
sub =  6 - 3 
s1 = str('2 + 4 = 6')
s2 = str('6 - 3 = 3')
s = str(suM) + str(sub)
print("The first number is: 2 \n The second number is 4 ")
print(s1 + "\n" + s2)
print('The concatenated result is: "'+s+'"')

# Introduction to data types
Data types are essential for how a program works. They serve different purposes, and it's important to choose the right data type for the job. 
If you pick the wrong one, it can seriously slow down a computer's performance.
Python has the following data types: integers, booleans, floating point numbers, complex numbers and strings
So, it's better to use integer variables from the start, which are more efficient for handling numbers. The main takeaway is that selecting the appropriate data type is crucial for a program to run efficiently.

#Integers
A company called BIG VEGGIE sells fresh food to smaller stores. BIG VEGGIE buys their stock in bulk. 
BIG VEGGIE has asked you to develop a system to calculate the amount small stores will have to pay. All stock items have a fixed price:
Asparagus – R30.54 per kg
Beetroot – R1.45 per kg
Broccoli – R14.43 per kg
Garlic – R35.81 per kg
Potatoes – R2.04 per kg
A store must buy more than 100 kg of broccoli in order to get a 20% discount. They must also buy more than 300 kg of potatoes in order to get a 30% discount. BIG VEGGIE has asked you to develop a program that will only ask them to input the weight for each product the store buys from them. The program must determine the total amount due. Presume you have to take more than 100 kg of broccoli, and more than 300 kg of potatoes. The rest of the products have a fixed price, independent of how much you buy. 

#CODE FOR BIG VEGGIE system
# price of veg per kg
asparagus = 30.54
beetroot = 1.45
broccolli = 14.43
garlic = 35.81
potatoes = 2.04
#asks for amount the store would like to buy (kg)
print("Enter the amount of asparagus (kg): ")
aspa = float(input())
print("Enter the amount of beetroot (kg): ")
beet = float(input())
print("Enter the amount of broccolli (kg): ")
broc = float(input())
print("Enter the amount of garlic (kg): ")
garl = float(input())
print("Enter the amount of potatoes (kg): ")
pota = float(input())
# calculates the total price for each vegetable and the amount of discount
aspa = aspa * asparagus
beet = beet * beetroot
b = (((broc * broccolli) * 20) / 100)
broc = (broc * broccolli) - b
garl = garl * garlic
p = (((pota * potatoes) * 30) / 100)
pota = (pota * potatoes) - p

total = aspa + beet + broc + garl + pota
print(f"The total the store has to pay: R {total}")

#Floating point numbers
print ("18 (decimal) as a octal value: %u" %18)
print ("37.0 (decimal) as a lowercase hexadecimal value: %x" % 37 )
print("4656 (float): (e) floating point exponential value: %e " %4656)

print("Today's dollar price compared to the Rand: R%.2f" %6.85871) # rounds off the output to 2 decimal places

#Result
18 (integer) as a octal value: 22
37 (integer) as a lowercase hexadecimal value: 25
4656 (float): (e) floating point exponential value: 4.656000e+03 
Today's dollar price compared to the Rand: R6.86

#Strings
Strings are made of Unicode characters, which are like building blocks for text. 
When we want to create an empty string, we can simply use str() or str(" ") – both do the same thing.
the ‘+=‘ operator adds values to an existing variable.
for example: sentence = "This sentence is way too long to fit on one line of" 
sentence += " code and that is why I'm breaking this sentence down"
The end of line escape sequence (\) also helps to make code more readable by breaking up the code onto multiple lines.

#Lambda expressions
It's possible to create anonymous functions using the "lambda" keyword. 
These functions are typically simple and return a result based on one expression, like "lambda a, b: a + b" which calculates the sum of two numbers. 
Lambda functions are handy when you need a quick function for a specific task.
Lambda functions are essentially a concise way to define small functions.

names = lambda fn, ln: fn.title() + " " + ln.title()
result = names("   makabongwe", "      metuso")
print(result)

#Week 2 (Control Flow)

Activity 1:
Using two for loops, write a program that produces the following output:
>>>

1 2 3

4 5 6

7 8 9

>>> 

for i in range(1, 10):
    print(i, end=' ')
    if i % 3 == 0:
        print()

Activity 2: 
Input in a number representing a car type, until the number 0 is input. 
There are three types of cars: 1 = luxury, 2 = commercial, 3 = sedan. 
Count how many of each type there are and print out this total with a message stating what type of car it is.

cars = {
  1: 0 ,
  2: 0,
  3: 0
}
while True:
  car_type = int(input("Enter car type (1 = luxury, 2 = commercial: "))
  if car_type == 1:
      print("Luxury")
  elif car_type == 2:
      print("Commercial")
  else:
    car_type == 0
    break
  cars[car_type] += 1
for car_type, count in cars.items():
  print(f"Number of {car_type} cars: {count}")

Activity 3: 
Write a program that contains a while loop. Use a variable to count the number of iterations and print out this value each time. 
After the fifth iteration, the loop should stop and exit. Use the break statement.

count = 0
while True:
    count += 1
    print(count)
    if count == 5:
        break

# Day 2 (Functions)

Functions are mainly used to avoid repetitive code and save memory. Instead of duplicating code, functions are created to encapsulate a specific operation. 
Functions can accept zero or more inputs, referred to as parameters, and are called whenever that particular operation is needed. 
This approach makes the code more efficient and easier to maintain by organizing it into reusable, modular pieces.

# Random module
Activity:
Write a program that requests the user to input three numbers. These numbers must be passed to two functions:
A function that calculates and prints the product of the numbers.
A second function that calculates and returns the average of the numbers.
The average returned by the function is then printed.

# Function for calculating product of 3 numbers and average
def numProd(n1, n2, n3):
  return n1 * n2 * n3
print("Enter 3 numbers: ")
print("Enter 1st number:")
n1 = int(input())
print("Enter 2nd number:")
n2 = int(input())
print("Enter 3rd number:")
n3 = int(input())
print(f"The product of the number is: {numProd(n1, n2, n3)}")

def numAve(n1, n2, n3):
  return (n1 + n2 + n3) / 3
print(f"The average of the number is: {numAve(n1, n2, n3)}")

#Recursive functions

Flags instruct the regex on how to operate when searching for patterns. 
When you use the IGNORECASE flag, you're instructing the compiler to perform a match that doesn't distinguish between uppercase and lowercase letters. 
This can lead to shorter regular expressions; for instance, [0-9a-zA-Z] can be simplified to [0-9a-z]. 
You can use re.I instead of re.IGNORECASE, and it will achieve the same outcome.
The VERBOSE flag enhances the readability of an expression by permitting the inclusion of comments and white spaces. 
You'd typically opt for the verbose flag when crafting a lengthy and intricate regular expression that requires clarification. 
The regex would interpret the expression as a standard one without any comments or spaces.


#Week 3 (Defining functions)

#Lists can be created in a number of ways:
f = [] # An empty list
fruits = ['apple', 'banana', 'mango']
fruits.append(['kiwi', 'pear'])
>>> fruits
['apple', 'banana', 'mango', ['kiwi', 'pear']] #A nested list
list = ['child', 1, 3.14] # A list with mixed data types

#Regular Expressions

Activity 1:
Write a program that removes all numbers (except 5) that appear in a string. The string = JGDN8923487854t6fnjhasfu555335udvb

import re
string = "JGDN8923487854t6fnjhasfu555335udvb"
updated_string = re.sub(r"[5]+", "", string)
print(updated_string)

Output: 
JGDN892348784t6fnjhasfu33udvb #All the digits = 5 have been removed

Activity 2: 
Write a program that prompts a user to enter a cell phone number in a certain format: +2778-123-4567
The number must start with "+27" (standard South-African number). A message must be printed indicating if the number is in the correct format.
An error message must be printed if the wrong country code is entered or the number is in an incorrect format

import re 
print("Enter a cell number:")
cell_num = input()

cell_num_pattern = re.match(r"^\+27\d{2}[-]\d{3}[-]\d{4}$", cell_num)

if cell_num_pattern:
    print("Valid phone number")
else:
    print("Invalid phone number")




The index operator ([])is used to retrieve an element from a list. Indexing begins at 0. 
Any attempt to access indices outside of this range will trigger an IndexError. 
Furthermore, the index must be an integer; using a float or other types will lead to a TypeError. 
When dealing with nested lists, you access them using nested indexing.
