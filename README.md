Download Link: https://assignmentchef.com/product/solved-comp-3350-hw-6-theme-arithmetic-and-procedures
<br>
<ol>

 <li>[Arithmetic Expression] Write a program that computes the following arithmetic expression:</li>

</ol>

EDX = Dog + Cat – Mouse + Horse




Use the following data definitions:

Dog SWORD    8

Cat SWORD   -25

Mouse SWORD   -36

Horse SWORD   -102




<ol>

 <li>[Arrays] Write a program that:</li>

</ol>




<ul>

 <li>Prompts the user for integer input 15 times</li>

 <li>Stores these inputs in an array</li>

 <li>Displays the stored array values on the screen using WriteInt (not DumpRegs).</li>

</ul>




In your submission, please embed the full program (.lst file) and one screen shot with at least one positive and one negative input value. Use the following:




.data

PromptUser  BYTE “Please enter a value:”, 0

Oranges     SWORD 15 DUP(?)







<ol>

 <li>[Compares, Procedures] Write a procedure, <em>MinMax</em> that computes the next to minimum and next to maximum values stored in the array<em> Oranges</em>.   Write a main program that calls <em>MinMax</em> and prints the values found.   Also, print the array indices at which the values were found.</li>

</ol>







Use the following:

.data

prompt      BYTE “Please input a value: “, 0

spacing     BYTE “, “,0;

Minimum     BYTE “The minimum value of inputs is:  and is located             at index: “,0

Maximum     BYTE “The maximum value of inputs is:  and is located             at index: “,0




In your submission, please embed the full program (.lst file) and one screen shot showing the values found.

Example:

Oranges SWORD 30, 60, 10, 40, 50, 20, 90, 100, 70, 80

Next to minimum 20

Next to maximum 90

Please test with positive and negative values







<ol>

 <li>Use a loop with indirect or indexed addressing to swap the odd indexed elements of an integer (word sizes) array in place as they occur.  Please print the original and the swapped arrays.  Please use several arrays with varying lengths to test your program.</li>

</ol>

Example:

Indices:                    0, 1,   2,   3,   4,   5,    6,  7,   8,  9

MyArray SWORD 10, 20, 30, 40 ,50, 60 ,70, 80 ,90 100

After Swaps:

MyArray SWORD  10, 40, 30, 20, 50, 80, 70, 60, 90, 100

Please note that the last index 9 value does not need to be swapped.


