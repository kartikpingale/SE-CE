1.
In Second year Computer Engineering class of M students, set A of students play cricket and set B of students play badminton. Write C/C++ program to find and display-
i. Set of students who play either cricket or badminton or both ii. Set of students who play both cricket and badminton
iii. Set of students who play only cricket
iv. Set of students who play only badminton
v. Number of students who play neither cricket nor badminton (Note- While realizing the set duplicate entries are to avoided)
2.
Write C/C++ program to store marks scored for first test of subject 'Data Structures and Algorithms' for N students. Compute
I. The average score of class
ii. Highest score and lowest score of class
iii. Marks scored by most of the students
iv. list of students who were absent for the test
 
3.
Department library has N books. Write C/C++ program to store the cost of books in array in ascending order. Books are to be arranged in descending order of their cost. Write function
for a) Reverse the contents of array without using temporary array. b) Copy costs of books those with cost less than 500 in new array c) Delete the duplicate entries using temporary array
d) Delete duplicate entries without using temporary array
e) Count number of books with cost more than 500.
4.
 
 Set A=(1,3, a, s, t, i} represent alphanumeric characters permitted to be used to set the password of length 4. Write C/C++ program to generate all possible passwords.
5.
A magazine committee is to be formed that consists of any 3 members to be selected from { Nikhita, Aboli, Megha, Sanika, Pratik, Saurabh}. Write C/C++ program to list all possible committees.
6.
 
 
It is decided that weekly greetings are to be furnished to wish the students having their birthdays in that week. The consolidated sorted list with desired categorical information is to be provided to the authority. Write C++ program for array of structures to store students PRNs with date and month of birth. Let Array_A and Array_B be the two arrays for two SE Computer divisions. Arrays are sorted on date and month. Merge these two arrays into third array Array_SE_Comp_DOB resulting in sorted information about Date of Birth of SE Computer students.
7.
A magic square is an n * n matrix of the integers 1 to n2 such that the sum of each row, column, and diagonal is the same. The figure given below is an example of magic square for case n=5. In this example, the common sum is 65. Write C/C++ Program for magic square.
        15
22
8
14
1
           16
7
24
  5
17
    23
      4
               3
20
21
13
6
  10
                    8.
9
2
19
25
12
    18
11
          An m x n matrix is said to have a saddle point if some entry a[i][j] is the smallest value in row i and the largest value in j. Write C/ C++ function that determines the location of a saddle point if one exists.
             9.
     10.
Write C/C++ program for storing matrix. Write functions for
a) Check whether given matrix is upper triangular or not b) Compute summation of diagonal elements
c) Compute transpose of matrix
d) Add, subtract and multiply two matrices
   Write C++ program with class for String. Write a function
 frequency that determines the frequency of occurrence of particular character in the
string.
 delete that accepts two integers, start and length. The function computes a new string
that is equivalent to the original string, except that length characters being at start have
been removed.
 chardelete that accepts a character c. The function returns the string with all occurrences
of c removed.
 replace to make an in-place replacement of a substring w of a string by the string x. note
that w may not be of same size of x
 palindrome to check whether given string is palindrome or not
        11.
12.
13.
1. 2. 3.
Write C++ program for sparse matrix realization and operations on it- Transpose, Fast Transpose and addition of two matrices
        Write C++ program for string operations- copy, concatenate, check substring, equal, reverse and length
        Write a C++ program to realize polynomial equation and perform operations. Write function a) To input and output polynomials represented as bmxem+ bm-1xem-1 +..... +b0xe0.
Your functions should overload the << and >> operators. b) Evaluates a polynomial at given value of x
c) Add two polynomials
d) Multiplies two polynomials
Group B
         Department of Computer Engineering has student's club named 'Pinnacle Club'. Students of Second, third and final year of department can be granted membership on request. Similarly one may cancel the membership of club. First node is reserved for president of club and last node is reserved for secretary of club. Write C++ program to maintain club member‘s information using singly linked list. Store student PRN and Name. Write functions to
         a) Add and delete the members as well as president or even secretary. b) Compute total number of members of club
c) Display members
d) Display list in reverse order using recursion
e) Two linked lists exists for two divisions. Concatenate two lists.
 
 15.
The ticket booking system of Cinemax theater has to be implemented using C++ program. There are 10 rows and 7 seats in each row. Doubly circular linked list has to be maintained to keep track of free seats at rows. Assume some random booking to start with. Use array to store pointers (Head pointer) to each row. On demand
a) The list of available seats is to be displayed b) The seats are to be booked
c) The booking can be cancelled.
 16.
Write C++ program for storing appointment schedule for day. Appointments are booked randomly using linked list. Set start and end time and min and max duration for visit slot. Write functions for-
a) Display free slots
b) Book appointment
c) Cancel appointment ( check validity, time bounds, availability etc) d) Sort list based on time
e) Sort list based on time using pointer manipulation
17.
Second year Computer Engineering class, set A of students like Vanilla Ice-cream and set B of students like butterscotch ice-cream. Write C/C++ program to store two sets using linked list. compute and display-
i. Set of students who like either vanilla or butterscotch or both ii. Set of students who like both vanilla and butterscotch
iii. Set of students who like only vanilla not butterscotch iv. Set of students who like only butterscotch not vanilla
v. Number of students who like neither vanilla nor butterscotch
 
18.
Write C++ program to store set of negative and positive numbers using linked list. Write functions to
a) Insert numbers
b) Delete nodes with negative numbers
c) Create two more linked lists using this list, one containing all positive numbers and other containing negative numbers
d) For two lists that are sorted; Merge these two lists into third resultant list that is sorted
 
19.
Write C++ program for storing binary number using doubly linked lists. Write functions-
a) to compute 1‘s and 2‘s complement b) add two binary numbers
20.
Let x = (x1,x2, ... , xn) and y = (y 1, y2,.... , ym) be two doubly linked lists. Assume that in each linked list, the nodes are in non-decreasing order of their data-field values. Write C/C++ program to merge the two lists to obtain a new linked list z in which the nodes are also in this order. Following the merge, x and y should represent empty lists because each node initially in x or y is now in z. No additional nodes may be used.
21.
Design a linked allocation system to represent and manipulate univariate polynomials with integer coefficients (use circular linked lists with head nodes). Each term of the polynomial will be represented as a node Thus. a node in this system will have three data members as below:
Exponent
Link
Coefficient
To erase polynomials efficiently, we need to use an available-space list and associated functions. The external (i.e.. for input or output) representation of a univariate polynomial will be assumed to be a sequence of integers of the form: n, c1, e1 ,c2. e2. c3. e3 . . , cn en where ei represents an exponent and ci a coefficient; n gives the number of terms in the polynomial. The exponents are in decreasing order — i.e., e1> e2> .... >en.
Write and test the following functions:
1. istream&operator >>(istream& is, Polynomial& x): Read in an input polynomial
and convert it to its circular list representation using a head node.
2. ostream&operator<< (ostream&os, Polynomial& x): Convert x from its linked list
representation to its external representation and output it.
3. Polynomial:: Polynomial(const Polynomial& a) [Copy Constructor]: Initialize the
polynomial *this to the polynomial a.
4. const Polynomial& Polynomial :: operator=(const Polynomial& a) [Assignment
Operator]: Assign polynomial a to*this.
5. Polynomial:: Polynomial ( ) [Destructor]: Return all nodes of the polynomial *this to
the available-space list.
6. Polynomial operator+ (const Polynomial& a, const Polynomial& b) [Addition]:
Create and return the polynomial a + b. a and b are to be left unaltered.
7. Polynomial operator* (constPolynomial& a, constPolynomial& b) [Multiplication]:
Create and return the polynomial a * b. a and b are to be left unaltered.
8. floatPolynomial ::Evaluate(float x): Evaluate the polynomial *this at x and return the
result.
 
22.
Write C++ program to realize Set using Generalized Liked List (GLL) Ex. A ={ a, b, {c, d,e, {}, {f,g}, h, I, {j,k}, l, m}. Store and print as set notation.
 
 
Group C
 
  23.
A palindrome is a string of character that‘s the same forward and backward. Typically, punctuation, capitalization, and spaces are ignored. For example, ‖Poor Dan is in a droop‖ is a palindrome, as can be seen by examining the characters ―poor danisina droop‖ and observing that they are the same forward and backward. One way to check for a palindrome is to reverse the characters in the string and then compare with them the original-in a palindrome, the sequence will be identical. Write C++ program with functions- 1. To check whether given string is palindrome or not that uses a stack to determine whether
a string is a palindrome.
2. to remove spaces and punctuation in string, convert all the Characters to lowercase, and
then call above Palindrome checking function to check for a palindrome 3. to print string in reverse order using stack
24.
In any language program mostly syntax error occurs due to unbalancing delimiter such as (),{},[]. Write C++ program using stack to check whether given expression is well parenthesized or not.
25.
Implement C++ program for expression conversion as infix to postfix and its evaluation using stack based on given conditions
i. Operands and operator, both must be single character. ii. Input Postfix expression must be in a desired format. iii. Only '+', '-', '*' and '/ ' operators are expected.
26.
 
 
Implement C++ program for expression conversion-
a) infix to prefix, b)prefix to postfix,
c) prefix to infix, d) postfix to infix and e) postfix to prefix.
27.
 
 
A classic problem that can be solved by backtracking is called the Eight Queens problem, which comes from the game of chess. The chess board consists of 64 square arranged in an
8 by 8 grid. The board normally alternates between black and white square, but this is not relevant for the present problem. The queen can move as far as she wants in any direction, as long as she follows a straight line, Vertically, horizontally, or diagonally. Write C++ program with recursive function for generating all possible configurations for 4-queen's problem.
 
 
Group D
 
  28.
Queues are frequently used in computer programming, and a typical example is the creation of a job queue by an operating system. If the operating system does not use priorities, then the jobs are processed in the order they enter the system. Write C++ program for simulating job queue. Write functions to add job and delete job from queue.
 29.
Write program to implement a priority queue in C++ using an inorder List to store the items in the queue. Create a class that includes the data items(which should be template) and the priority (which should be int)The inorder list should contain these objects ,with operator <= overloaded so that the items with highest priority appear at the beginning of the list (which will make it relatively easy to retrieve the highest item.)
30.
A double-ended queue(deque) is a linear list in which additions and deletions may be made at either end. Obtain a data representation mapping a deque into a one-dimensional array. Write C++ program to simulate deque with functions to add and delete elements from either end of the deque.
 
31.
Pizza parlor accepting maximum M orders. Orders are served in first come first served basis. Order once placed cannot be cancelled. Write C++ program to simulate the system using circular queue using array.
 
 
Group E
  
 32.
Write C++ program to store roll numbers of student in array who attended training program in random order. Write function for-
a) Searching whether particular student attended training program or not using linear search and sentinel search. b) Searching whether particular student attended training program or not using binary search and Fibonacci search.
33.
Write C++ program to store names and mobile numbers of your friends in sorted order on names. a) Search your friend from list using binary search (recursive and non recursive). Insert friend if not present in phonebook. b) Search your friend from list using Fibonacci search. Insert friend if not present in phonebook.
 
34.
Write C++ program to maintain club members, sort on roll numbers in ascending order. Write function  ̳Ternary_Search‘ to search whether particular student is member of club. Ternary search is modified binary search that divides array into 3 halves instead of two.
 
35.
Write C++ program to store first year percentage of students in array. Write function for sorting array of floating point numbers in ascending order using
a) Selection Sort b) Bubble sort and display top five scores.
36.
Write C++ program to store second year percentage of students in array. Write function for sorting array of floating point numbers in ascending order using
a) Insertion sort b) Shell Sort and display top five scores.
37.
Write C++ program to store first year percentage of students in array. Sort array of floating point numbers in ascending order using quick sort and display top five scores.
38.
 
 
Write C++ program to store XII percentage of students in array. Sort array of floating point numbers in ascending order using bucket sort and display top five scores.
39.
 
 
Write C++ program to store X percentage of students in array. Sort array of floating point numbers in ascending order using radix sort and display top five scores.
