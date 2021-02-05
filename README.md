## SDSS Computing Studies Python Assignment
### Assignment #1 Basic Output (Total Marks 10)

Objectives:
* Create a repository and edit the files inside it
* Make use of the print() function to generate output

This assignment will test the basic structure of a python program.  
You will need to have proper structure and the recommended basic output.

### 3 Tasks

##### Task 1
(2 points) Modify the existing assignment file called "assignment.py".  It should display the message "Hello World!"

Sample Output Task #1
```
Hello World!
```

##### Task 2
(2 points) Create a new assignment file called "assignment2.py".  It should display the following:

Sample Output Task #2
```
This is my second program.
It uses "two commands" to display the output.
```
Note that you can't use the command print("It uses "two commands" to display the output.") because the Python3 interpreter sees the second double quotation is ending the first one.  In this case, we have two choices:
  - Use a single quotation mark as the beginning and end of the output string.
  - "Escape" the internal double quotation mark.  Using \" instead of " will tell the compiler that the double quote is for display, and is not functional

##### Task 3
(2 points) Modify the assignment file called "assignment3.py".  Add **,end=""** inside your print statements and modify the output string to force them to be printed on the same line.  Add an additional print statement so that the combined output is the following:

Sample Output Task #3
```
Hello world! This is how multiple print statements are joined. Use end=""
```

(4 points) You will receive the remaining 4 points in this assignment for successfully committing your files to Github and running your code through the "autochecker" to make sure you have met the assignment criteria.
