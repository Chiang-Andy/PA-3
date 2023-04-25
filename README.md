# CS-457 Programming Assignment 2: Basic Data Manipulation
# Build Environment
Visual Studio Code

python 3.8.2
# Executable & Compiling
To compile files: Type ' python3 -m main.py db.py query.py table.py ' into the terminal

To execute files: After compiling, the program should execute.

# Running The Program
After launching the executable, you should now be able to copy and paste each line from the sql file. Each expected output has been reach from my testing.

# Documentation/Notes
The system design is a simple design managing datable and tables.
My program has a simple way of organizing multiple databases by creating directories for them.
And multiple tables are handled by pushing them into a vector of table classes. 

My program now works in python with a tuple system to store items in a variable.
Directories is created and saved by storing the name of the database. Name of any database created is saved in the program and can be accessed for future uses.
After such, using a name directory, table is created by finding the name of the data and creating the table under the database filename. Data is parsed to pass in for use. And removing a table is done by using a simple remove function.

Table values are saved within index and place in a tuple similar to project 1 vector system. 
Select allows you to find the table index if it exists by looking through the tuple.
Altering table is done similarily to select as it grabs the values in the table index, but differs by changing the values within the table index.
