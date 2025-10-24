# Assignment_10
## Q1. Write a C++ program to define a structure Itemwith members id (integer), name (string), and cost (float). Declare an array of 8 Item structures, read their details from user input, and then:

  (a) Sort the array in descending order of cost.

  (b) Display the sorted list of items.

  (c) Additionally, display the average cost of all items.

### Test Case:
```text
Enter details of 8 items:

Item 1:
ID: 101
Name: Pen
Cost: 10.5

Item 2:
ID: 102
Name: Notebook
Cost: 35.0

Item 3:
ID: 103
Name: Pencil
Cost: 5.0

Item 4:

ID: 104
Name: Eraser
Cost: 3.5
Item 5:

ID: 105
Name: Marker
Cost: 25.0
Item 6:

ID: 106
Name: Ruler
Cost: 12.0
Item 7:

ID: 107
Name: Sharpener
Cost: 6.0
Item 8:

ID: 108
Name: File
Cost: 40.0

Output:

Items sorted in descending order of cost:
ID        Name           Cost      
--------------------------------------
108       File           40.00     
102       Notebook       35.00     
105       Marker         25.00     
106       Ruler          12.00     
101       Pen            10.50     
107       Sharpener      6.00      
103       Pencil         5.00      
104       Eraser         3.50      

Average cost of all items: 17.125

```

## Q2. Define two structures:

   Marks with members math, science, and english (floats).

   Student with members rollNo (int), name(string), and marks (of type Marks).

   Declare an array of 5 Student structures. Accept input for all students and their marks, compute their average marks, and then display:

  (a) The student with the highest average marks, and

  (b) The student with the lowest average marks.

### Test Case:
```text
Roll No: 1
Name: Riya
Math: 90
Science: 85
English: 88

Roll No: 2
Name: Karan
Math: 70
Science: 65
English: 72

Roll No: 3
Name: Neha
Math: 95
Science: 92
English: 96

Roll No: 4
Name: Arjun
Math: 55
Science: 60
English: 58

Roll No: 5
Name: Meena
Math: 80
Science: 78
English: 82

Output:

Student with Highest Average Marks:
Roll No: 3
Name: Neha
Average Marks: 94.33

Student with Lowest Average Marks:
Roll No: 4
Name: Arjun
Average Marks: 57.67
```
## Q3. Define a structure Employee with members id(int), name (string), and salary (float). Declare an array of 5 employees and read their details from user input. Write a menu-driven program that allows the user to:

(a) Display all employee details.

(b) Search for an employee by id.

(c) Increase the salary of all employees earning less than ₹30,000 by 10%.

(d) Exit.

### Test Case:
```text
Employee 1:
ID: 101
Name: Riya
Salary: 28000

Employee 2:
ID: 102
Name: Karan
Salary: 32000

Employee 3:
ID: 103
Name: Neha
Salary: 25000

Employee 4:
ID: 104
Name: Arjun
Salary: 30000

Employee 5:
ID: 105
Name: Meena
Salary: 27000

Output:
==============================
 Employee Menu 
==============================
1. Display all employee details
2. Search employee by ID
3. Increase salary (< ₹30,000) by 10%
4. Exit
Enter your choice: 2

Enter Employee ID to search: 104

Employee Found:
ID: 104
Name: Arjun
Salary: 30000.00
```
## Q4. Define a structure SalesRecord with members month (string), amount (float). Allow the user to input the sales data for all 12 months, and then:

  (a) Write all data to a text file named "sales_data.txt".

  (b) Read the data back from the file.

  (c) Display the month(s) where sales were above the yearly average.
