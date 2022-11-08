## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?

A1. Python is a high-level programming language designed to be easy to read and simple to implement.
	Python is also portable, meaning that it can run on any platform, including Windows, Mac, Linux etc.
	Python is a general-purpose language, meaning it can be used to create a variety of different programs and isn’t specialized for any specific problems. 
	This versatility, along with its beginner-friendliness, has made it one of the most-used programming languages today.


Q2. Why is Python called a dynamically typed language?

A2. Python don't have any problem even if we don't declare the type of variable. 
	It states the kind of variable in the runtime of the program. 
	Python also take cares of the memory management which is crucial in programming. So, Python is a dynamically typed language. 


Q3. List some pros and cons of Python programming language?

A3.
	Pros:
	Easy to Read, Learn and Write
	Improved Productivity
	Interpreted Language
	Flexible and Extensible
	Vast Libraries Support
	Embeddable
	Highly Scalable
	Portability
	
	Cons:
	Slower than compiled languages
	Design restrictions
	Large memory consumption
	Weak in Mobile Computing
	Weak database access layers
	Security
	Complex multithreading
	Garbage collection leads to potential memory losses


Q4. In what all domains can we use Python?

A4.	Machine learning / Artificial intelligence
	Data analytics and data visualization 
	Web development
	Game development
	Mobile app development
	Embedded systems
	Desktop GUI
	
	
Q5. What are variable and how can we declare them?

A5. Variables are containers for storing data values.
	Python is not “statically typed”. We do not need to declare variables before using them or declare their type. 
	A variable is created the moment we first assign a value to it. 
	A Python variable is a name given to a memory location. It is the basic unit of storage in a program.


Q6. How can we take an input from the user in Python?

A6. we can take input from the user using 'input()' function in Python.


Q7. What is the default datatype of the value that has been taken as an input using input() function?

A7. String is the default datatype.


Q8. What is type casting?

A8. Type Casting is the method to convert the variable data type into a certain data type in order to the operation required to be performed by users.

	There can be two types of Type Casting in Python –
	Implicit Type Casting(Python converts data type into another data type automatically. In this process, users don’t have to involve in this process.)
	Explicit Type Casting(Python need user involvement to convert the variable data type into certain data type in order to the operation required.)


Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?

A9. Yes, we can take more than one input from the user.
	
	In Python user can take multiple values or inputs in one line by two methods. 
	1.split() method(This method breaks the given input by the specified separator. If a separator is not provided then any white space is a separator.)
	2.List comprehension(This method is an elegant way to define and create list in Python. We can create lists just like mathematical statements in one line only. )


Q10. What are keywords?

A10. Python keywords are special reserved words that have specific meanings and purposes and can’t be used for anything but those specific purposes.


Q11. Can we use keywords as a variable? Support your answer with reason.

A11. We cannot use keywords as variable names. It's because keywords have predefined meanings.
	 Keywords are used to define the syntax and structure of the Python language.


Q12. What is indentation? What's the use of indentaion in Python?

A12. Indentation refers to the spaces at the beginning of a code line.
	 Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important.
	 Python uses indentation to indicate a block of code.


Q13. How can we throw some output in Python?

A13. 'print()' function is used to show output in Python


Q14. What are operators in Python?

A14. Operators are special symbols in Python that carry out arithmetic or logical computation. 
	 The value that the operator operates on is called the operand.
	 
	 Below are the different types of operators:
	 
	 Arithmetic operators(+,-,*,/,%,//,**)
	 Comparison operators(>,<,==,!=,>=,<=)
	 Logical operators(and, or, not)
	 Bitwise operators(&,|, ~,^,>>,<<)
	 Assignment operators(=, +=, -=, *=, /=, %=, //=, **=, &=, |=, ^=, >>=, <<=)
	 Identity operators(is, is not)


Q15. What is difference between / and // operators?

A15. '/'  - Float Division
	 '//' - Integer Division

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
A16.	print("iNeuron"*4)


Q17. Write a code to take a number as an input from the user and check if the number is odd or even.

A17.
	number = int(input("Enter a number: "))

	if(number%2 == 0):
		print(number,"is Even")
	else:
		print(number,"is Odd")


Q18. What are boolean operator?

A18. The logical operators (and, or and not) are also known as boolean operators.

Q19. What will the output of the following?
```
1 or 0 -- True

0 and 0  -- False

True and False and True -- False

1 or 0 or 0 -- True
```

Q20. What are conditional statements in Python?

A20. 'if' 'elif' and 'else' are conditional statements which is used in Python for decision making, when you want to execute code based on a particular condition.


Q21. What is use of 'if', 'elif' and 'else' keywords?

A21.
	These keywords allows us to check for multiple expressions. If the condition for 'if' is False , it checks the condition of the next 'elif' block and so on. If all the conditions are False , the body of 'else' is executed.

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".

A22. 
	age = int(input("Enter Age: "))
	 
	if age>=18:
		print("I can vote")
	else:
		print("I can't vote")


Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
A23.
	numbers = [12, 75, 150, 180, 145, 525, 50]
	sum = 0
	for i in numbers:
		if(i % 2 == 0):
			sum += i

	print("Sum of even numbers:",sum)


Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

A24.
	first = int(input("Enter First Number:"))
	second = int(input("Enter Second Number:"))
	third = int(input("Enter Third Number:"))

	if(first > second and first > third):
		print(first,"is greater")
	elif(second > third):
		print(second,"is greater")
	else:
		print(third,"is greater")


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
A25.
	numbers = [12, 75, 150, 180, 145, 525, 50]
	my_list = []
	for i in numbers:
		if(i > 500):
			break
		if(i > 150):
			continue
		if(i%5 == 0):
			my_list.append(i)

	print(my_list)