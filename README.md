This repo contains files on exercises regarding python programming with Coursera:Meta.
This README.md file will constantly be edited as need be.

0-ordering_system.py :Functions, loops and data structures
In this lab you will be presented with a menu ordering system which will allow users to input three choices for a select menu. You are tasked with completing the menu system so that it returns and calculates the final bill for the user.

Objectives
Create new functions to solve specific problems.

Gain experience of using for loops to iterate over different data collections.

Create and use data structures to store, retrieve and loop over data.

Instructions
Step 1: Open the script ordering_system.py present inside the project folder.

Step 2: Run the script and, when requested, enter in the three products of your choice based on the menu - 1 = espresso, 2 = coffee etc.

Step 3: To run the script, open the terminal and execute the command below.

python3 ordering_system.py



1-file_ops.py :Read in data, store, manipulate and output new data to a file
In this lab you must read the contents of a file and then write the contents to another file. You must also store the contents of a file into a list so that it can be accessed in different ways.

Goal
Use the open function for reading and writing files.

Objectives
Create a function for reading in a file.

Create a function for writing files.

Instructions
Step 1: Check that the sampletext.txt and file_ops.py files exist and are present inside the project folder. You can run the file_ops.py file by opening a terminal and executing the python3 file_ops.py command.
Step 2: Complete the read_file() function to read in the sampletext.txt file using the open function and return the entire contents of the file.

Step 3: Complete the read_file_into_line() function so that it returns a data structure of all the contents of the file in a line-by-line sequential order.

Step 4: Fill in the write_first_line_to_file() that accepts two arguments: the contents of a file to be written and the name of an output file, and writes only the first line of the file contents into the given output file.

Step 5: Complete the read_even_numbered_lines() to return a list of the even-numbered lines of a file (2, 4, 6, etc.)

Step 6: Fill in the read_file_in_reverse() function to return a list of the lines of a file in reverse order.


2-comprehensions.py :Mapping key-values to Dictionary data structures:
Instructions
Step 1: Open the comprehensions.py file

Step 2: Implement the to_mod_list() function by using the map() function to apply mod() to all elements within employee_list. Assign the result of it to a new variable called map_emp. Convert map_emp to a list and return it.

The mod() function returns a string value for example such as “Lisa_Cold Storage” from the dictionary passed to it. 

Step 3: At this point you should have a list of the values such as: “Lisa_Cold Storage” mentioned above. But that is no good for a username with the whitespace present in it. Implement the generate_usernames() method by using list comprehension and the replace()  over mod_list to replace all spaces (" ") with underscores ("_"). Return the resulting list.

Step 4: We want to create a dictionary that stores employees' first initials and IDs. Implement map_id_to_initial() by using dictionary comprehension over the employee_list to create a dictionary where each key is the first letter of an employee's name and the value is the employee's ID.
