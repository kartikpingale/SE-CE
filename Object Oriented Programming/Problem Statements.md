Implement a class Complex which represents the Complex Number data type. Implement the following operations:
1. Constructor (including a default constructor which creates the complex number 0+0i).
2. Overloaded operator+ to add two complex numbers.
3. Overloaded operator* to multiply two complex numbers. 4. Overloaded << and >> to print and read Complex Numbers.
          2.
           Implement a class Quadratic that represents degree two polynomials i.e., polynomials of type ax2+bx+c. The class will require three data members corresponding to a, b and c. Implement the following operations:
1. A constructor (including a default constructor which creates the 0 polynomial).
2. Overloaded operator+ to add two polynomials of degree 2.
3. Overloaded << and >> to print and read polynomials. To do this, you will need to
decide what you want your input and output format to look like.
4. A function eval that computes the value of a polynomial for a given value of x. 5. A function that computes the two solutions of the equation ax2+bx+c=0.
  3.
   Implement a class CppArray which is identical to a one-dimensional C++ array (i.e., the index set is a set of consecutive integers starting at 0) except for the following :
1. It performs range checking.
2. It allows one to be assigned to another array through the use of the assignment
operator (e.g. cp1= cp2)
3. It supports a function that returns the size of the array.
4. It allows the reading or printing of array through the use of cout and cin.
          4.
  Write a C++ program create a calculator for an arithmetic operator (+, -, *, /). The program should take two operands from user and performs the operation on those two operands depending upon the operator entered by user. Use a switch statement to select the operation. Finally, display the result.
Some sample interaction with the program might look like this:
Enter first number, operator, second number: 10 / 3 Answer = 3.333333
Do another (y/n)? y
Enter first number, operator, second number: 12 + 100 Answer = 112
Do another (y/n)? n
Develop an object oriented program in C++ to create a database of student information system containing the following information: Name, Roll number, Class, division, Date of Birth, Blood group, Contact address, telephone number, driving license no. etc Construct the database with suitable member functions for initializing and destroying the data viz constructor, default constructor, Copy constructor, destructor, static member functions, friend class, this pointer, inline code and dynamic memory allocation operators-new and delete.
7.
 
Create a class template to represent a generic vector. Include following member functions:
 To create the vector.
 To modify the value of a given element
 To multiply by a scalar value
 To display the vector in the form (10,20,30,...)
 
8.
 
Create a class Rational Number (fractions) with the following capabilities:
a) Create a constructor that prevents a 0 denominator in a fraction, reduces or simplifies fractions that are not in reduced form and avoids negative denominators.
b) Overload the addition, subtraction, multiplication and division operators for this class.
c) Overload the relational and equality operators for this class.
 
 
9.
 
Imagine a publishing company which does marketing for book and audiocassette versions. Create a class publication that stores the title (a string) and price (type float) of a publication. From this class derive two classes: book, which adds a page count (type int), and tape, which adds a playing time in minutes (type float).
Write a program that instantiates the book and tape classes, allows user to enter data and displays the data members. If an exception is caught, replace all the data member values with zero values.
 
10.
 Write a function in C++ to count and display the number of lines not starting with alphabet 'A' present in a text file "STORY.TXT".
Example:
If the file "STORY.TXT" contains the following lines,
The roses are red.
A girl is playing there.
There is a playground.
An aeroplane is in the sky.
Numbers are not allowed in the password. The function should display the output as 3.
11.
 
Write C++ Program with base class convert declares two variables, val1 and val2, which hold the initial and converted values, respectively. It also defines the functions getinit( ) and getconv( ), which return the initial value and the converted value. These elements of convert are fixed and applicable to all derived classes that will inherit convert. However, the function that will actually perform the conversion, compute( ), is a pure virtual function that must be defined by the classes derived from convert. The specific nature of compute( ) will be determined by what type of conversion is taking place.
A book shop maintains the inventory of books that are being sold at the shop. The list includes details such as author, title, price, publisher and stock position. Whenever a customer wants a book, the sales person inputs the title and author and the system searches the list and displays whether it is available or not. If it is not, an appropriate message is displayed. If it is, then the system displays the book details and requests for the number of copies required. If the requested copies book details and requests for the number of copies required. If the requested copies are available, the total cost of the requested copies is displayed; otherwise the message ―Required copies not in stock‖ is displayed. Design a system using a class called books with suitable member functions and Constructors. Use new operator in constructors to allocate memory space required. Implement C++ program for the system.
 
13.
 
Create employee bio-data using following classes i) Personal record ii))Professional record iii) Academic record Assume appropriate data members and member function to accept required data & print bio-data. Create bio-data using multiple inheritance using C++.
 
 
Group B
 
 
14.
 
Crete User defined exception to check the following conditions and throw the exception if the criterion does not meet.
a. User has age between 18 and 55
b. User stays has income between Rs. 50,000 – Rs. 1,00,000 per month c. User stays in Pune/ Mumbai/ Bangalore / Chennai
d. User has 4-wheeler
Accept age, Income, City, Vehicle from the user and check for the conditions mentioned above. If any of the condition not met then throw the exception.
 
15.
 Write a menu driven program that will create a data file containing the list of telephone numbers in the following form
John 23456 Ahmed 9876
........... .........
Use a class object to store each set of data, access the file created and implement the following tasks
I. Determine the telephone number of specified person
II. Determine the name if telephone number is known
III. Update the telephone number, whenever there is a change.
16.
 
 
Write a C++ program that creates an output file, writes information to it, closes the file and open it again as an input file and read the information from the file.
 
17.
 Write a C++ program using command line arguments to search for a word in a file and replace it with the specified word. The usage of the program is shown below.
$ change <old word> <new word> <file name>
18.
 
Write a function template selection Sort. Write a program that inputs, sorts and outputs an integer array and a float array.
You are the owner of a hardware store and need to keep an inventory that can tell you what different tools you have, how many of each you have on hand and the cost of each one. Write a program that initializes the random-access file hardware.dat to 100 empty records, lets you input the data concerning each tool, enables you to list all your tools, lets you delete a record for a tool that you no longer have and lets you update any information in the file. The tool
          19.
identification your file:
Record #
3 17 24 39 56
number should be the record number. Use the following information to start
  Tool name Quantity
Electric sander 7 Hammer 76 Jig saw 21 Lawn mower 3 Power saw 18
Cost
57.98 11.99 11.00 79.50 99.99
                                                     Group C
       20.
Write C++ program using STL for implementation of Singly, doubly and circular linked list.
                          21.
Write C++ program using STL for implementation of stack & queue using SLL
      Write C++ program using STL to add binary numbers (assume one bit as one number); use STL stack.
           22.
             23.
Write C++ program using STL for Dqueue (Double ended queue)
    Write C++ program using STL for Sorting and searching with user-defined records such as Person Record (Name, birth date, telephone no), item record (item code, item name, quantity and cost)
          24.
          Mini-projects
              25.
Design and develop the Tic-Tac-Toe Game using C++
      Develop a Supermarket Billing System using C++. The key features of this application are listed below :
 Bill Report: It shows the bill report of all the items added in supermarket billing system.
 Add, Remove or Edit items: With this feature one can add, remove and modify item details. In add items, one can add information or details such as item no., item name, manufacturing date, price, quantity, tax percent, and many more.
 Show item details: This feature allows users to see the items and the corresponding details given for the item while adding the item.
Use file to store the data.
          26.
  Design an E-mail Verifier which accepts the email address from the user. Depending upon the input given by user display appropriate results. Use the following concepts in the Project – Constructor, Destructor, new, delete, exceptional handling, string handling functions, etc.
          27.
            28.
Design and Develop Library Management system using OOP Concepts.
    Write a C++ program to implement a small database mini project to understand persistent objects and operations on sequential files (ex- library information, inventory systems, automated banking system, reservation systems etc.) For example, write a program to create a database for reservation system using information such as Name, sex, age, starting place of journey and destination. Program should have following facilities a) To display entire passenger list b) To display particular record c) To update record d) To delete and sort record. Use Exception Handling for data verification
