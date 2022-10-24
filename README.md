This repo contains files on exercises regarding python programming with Coursera:Meta.
This README.md file will constantly be edited as need be.

# 0-ordering_system.py : Functions, loops and data structures
## Lab Instructions
In this lab you will be presented with a menu ordering system which will allow users to input three choices for a select menu. You are tasked with completing the menu system so that it returns and calculates the final bill for the user.

## Objectives
Create new functions to solve specific problems.
Gain experience of using for loops to iterate over different data collections.
Create and use data structures to store, retrieve and loop over data.

## Instructions
1. Open the script ordering_system.py present inside the project folder.
2. Run the script and, when requested, enter in the three products of your choice based on the menu - 1 = espresso, 2 = coffee etc.
3. To run the script, open the terminal and execute the command below:
python3 ordering_system.py
<hr>



# 1-file_ops.py :Read in data, store, manipulate and output new data to a file
## Lab Instructions
In this lab you must read the contents of a file and then write the contents to another file. You must also store the contents of a file into a list so that it can be accessed in different ways.

## Goal
Use the open function for reading and writing files.
## Objectives
Create a function for reading in a file.
Create a function for writing files.

## Instructions
1. Check that the sampletext.txt and file_ops.py files exist and are present inside the project folder. You can run the file_ops.py file by opening a terminal and executing the python3 file_ops.py command.
2. Complete the read_file() function to read in the sampletext.txt file using the open function and return the entire contents of the file.
3. Complete the read_file_into_line() function so that it returns a data structure of all the contents of the file in a line-by-line sequential order.
4. Fill in the write_first_line_to_file() that accepts two arguments: the contents of a file to be written and the name of an output file, and writes only the first line of the file contents into the given output file.###Note that I have'nt been able to make this line work properly
5. Complete the read_even_numbered_lines() to return a list of the even-numbered lines of a file (2, 4, 6, etc.)
6. Fill in the read_file_in_reverse() function to return a list of the lines of a file in reverse order.
<hr>



# 2-comprehensions.py :Mapping key-values to Dictionary data structures
## Instructions
1. Open the comprehensions.py file
2. Implement the `to_mod_list()` function by using the `map()` function to apply `mod()` to all elements within employee_list. Assign the result of it to a new variable called map_emp. Convert map_emp to a list and return it.
The `mod()` function returns a string value for example such as “Lisa_Cold Storage” from the dictionary passed to it. 
3. At this point you should have a list of the values such as: “Lisa_Cold Storage” mentioned above. But that is no good for a username with the whitespace present in it. Implement `the generate_usernames()` method by using list comprehension and the `replace()`  over mod_list to replace all spaces (" ") with underscores ("_"). Return the resulting list.
4. We want to create a dictionary that stores employees' first initials and IDs. Implement `map_id_to_initial()` by using dictionary comprehension over the employee_list to create a dictionary where each key is the first letter of an employee's name and the value is the employee's ID.
<hr>


# 3-bank.py :Abstract Classes and Methods
## Lab Instructions
In this assignment, you will be creating an abstract class for a bank that will be used to create a regular class for a specific bank. This class will contain the implementation of the abstract method from the abstract class.  
## Instructions
1. Create a class called Bank and pass ABC to it. 
2. Inside the class you have to define two methods: 
2.1 Define a function called basicinfo() and add a print statement inside it saying "This is a generic bank" and returning the string "Generic bank: 0"  
2.2 Define a second function called withdraw and keep it empty by adding a pass keyword under it. Make this function abstract by adding '@abstractmethod' right above it. 
3. Create another class called Swiss and pass the class Bank inside it. This means you are inheriting from class Bank.  
3.1 Create a constructor for this class that initializes a class variable `bal` to 1000
4. Override both functions from the Bank class: basicinfo() and withdraw(). 
4.1 Define a function called basicinfo() and add a print statement inside it stating “This is the Swiss Bank” and returning a string with "Swiss Bank: " followed by the current bank balance. For example, if self.bal = 80, then it would return "Swiss Bank: 80"
4.2 Define a second function,  called withdraw and pass one parameter to it (other than self): amount. Amount represents the amount that will be withdrawn. 
4.2.1 Update the class variable bal by deducting the value of amount from it. 
4.2.2 Print the value of amount giving output such as: “Withdrawn amount: 30"
4.2.3 Print the new balance giving an output such as: “New balance: 970”
4.2.4 Return the new balance
Note: Make sure to verify that there is enough money to withdraw! If amount is greater than balance, then do not deduct any money from the class variable bal, print a statement saying "Insufficient funds",  and return the original account balance instead.
