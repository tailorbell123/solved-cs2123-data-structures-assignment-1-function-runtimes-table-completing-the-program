Download Link: https://assignmentchef.com/product/solved-cs2123-data-structures-assignment-1-function-runtimes-table-completing-the-program
<br>
This program prints a table of runtimes (these are displayed in seconds) for given functions on arrays. The program tests different array sizes to establish a relationship between input size and runtime. It tests each array size multiple times and then takes an average of the times. Here are example calls to the timing functions:

int sizes[] = { 1000, 2500, 5000, 7500, 10000}; char str1[] = “Insertion Sort”; char str2[] = “quicksort (uses insertion sort when sorting &lt;30 numbers)”;

fRT = timeAlgorithm(str1, 10, 5, sizes, insertionSortInitial ); printRuntimeTable(fRT); freeFunctionRuntimes(fRT);

fRT = timeAlgorithm(str2, 10, 5, sizes, quickSortOptInitial ); printRuntimeTable(fRT); freeFunctionRuntimes(fRT); This results in following table:

Note your runtimes may vary since the test data is randomly generated.

The runtimes are stored in a functionRuntimes struct. You are completing a program to create and fill data in this struct, print the data of this struct, and free this struct.

You are given a partial implementation in the fle “cs2123HW1-LastName.c”. Specifically you are tasked to complete the funtctions below the heading “Functions for finding and printing runtime”. No other functions should be changed.

<strong>Using the Program (5 points)</strong>

After you have the program completed, you should use it to help determine the asymptotic runtimes of the three mystery functions (i.e., mysteryRuntime1, mysteryRuntime2, mysteryRuntime3).

Be sure to also examine the code of the mystery functions to confirm/improve your estimations.

Fill in the following table in the provided file:

/*

TODO: Give your asymptotic estimates for the runtimes of the following 3 functions:

mysteryRuntime1: O( ) mysteryRuntime2: O(  ) mysteryRuntime3: O( )

*/

<strong>Deliverables:</strong>

Your solution should be submitted as “cs2123HW1-LastName.c” where “LastName” is replaced with your last name. Be sure to fill in the table of runtimes described above:

Upload this file to Blackboard under Assignment 1. <strong>Do not zip your file</strong>.

To receive full credit, your code must compile and execute. You should use valgrind to ensure that you do not have any memory leaks.


