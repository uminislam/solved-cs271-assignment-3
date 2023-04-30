Download Link: https://assignmentchef.com/product/solved-cs271-assignment-3
<br>
Write and test a MASM program to perform the following tasks:

<ol>

 <li>Display the program title and programmer’s name.</li>

 <li>Get the user’s name, and greet the user.</li>

 <li>Display instructions for the user.</li>

 <li>Repeatedly prompt the user to enter a number. Validate the user input to be in [-100, -1] (inclusive).  Count and accumulate the valid user numbers until a non-negative number is entered.  (The nonnegative number is discarded.)</li>

 <li>Calculate the (rounded integer) average of the negative numbers.</li>

 <li>Display:

  <ol>

   <li>the number of negative numbers entered (Note: if no negative numbers were entered, display a special message and skip to )</li>

   <li>the sum of negative numbers entered</li>

  </ol></li>

</ol>

<ul>

 <li>the average, rounded to the nearest integer (e.g. -20.5 rounds to -20)</li>

</ul>

<ol>

 <li>a parting message (with the user’s name)</li>

</ol>




<strong>Requirements</strong>:

<ol>

 <li>The <em>main</em> procedure must be modularized into <u>commented logical sections</u> (procedures are not required this time)</li>

 <li>The program must be fully documented. This includes a complete header block for identification, description, etc., and a comment outline to explain each section of code.</li>

 <li>The lower limit should be defined as a <u>constant</u>.</li>

 <li>The usual requirements regarding documentation, readability, user-friendliness, etc., apply.</li>

 <li>Submit your text code file (.<em>asm</em>) to Canvas by the due date.</li>

</ol>

<strong> </strong>

<strong>Notes</strong>:

<ol>

 <li>There are no new concepts in this programming assignment. It is given for extra practice, to keep MASM fresh in your mind while we study internal/external data representation.</li>

 <li>This is an integer program. Even though it would make more sense to use floating-point computations, you are <strong>required</strong> to do this one with integers.</li>

</ol>




<strong>Example</strong> (see next page)<strong>                                                 </strong>

page 1 of 2

<strong>Example</strong> (user input in <strong><em>italics</em></strong>):

Welcome to the Integer Accumulator by Austin Miller

What is your name? <strong><em>Caleb</em></strong>

Hello, Caleb




Please enter numbers in [-100, -1].

Enter a non-negative number when you are finished to see results.

Enter number: –<strong><em>15</em></strong>

Enter number: –<strong><em>100</em></strong> Enter number: –<strong><em>36</em></strong>

Enter number: <strong><em>-10</em></strong>

Enter number: <strong><em>0</em></strong>

You entered 4 valid numbers.

The sum of your valid numbers is -161

The rounded average is -40

Thank you for playing Integer Accumulator! It’s been a pleasure to meet you, Caleb.




<strong>Extra-credit options </strong>(original definition must be fulfilled):

<ol>

 <li>Number the lines during user input.</li>

 <li>Calculate and display the average as a floating-point number, rounded to the nearest .001.</li>

 <li>Do something astoundingly creative.</li>

</ol>