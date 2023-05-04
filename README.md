Download Link: https://assignmentchef.com/product/solved-csc-110-fundamentals-of-programming-i-assignment-2-static-methods-scanners-for-loops
<br>
<h1>Learning outcomes</h1>

When you have completed this assignment, you should understand:

<ul>

 <li>How to <em>evaluate expressions</em>.</li>

 <li>How to use a <em>for-loop</em> to repeat operations.</li>

 <li>How to write and call a <em>static method</em>.</li>

 <li>How to <em>design, compile, run and check</em> a simple and complete Java program on your own.</li>

 <li>How to <em>input data from the console</em>.</li>

 <li>How to use <em>String methods</em>.</li>

 <li>How to <em>indent and document</em> a Java program.</li>

</ul>







<strong>             </strong>

Create a Java program named <em>FoxSays.java</em>. The program will request user input from the command line, and the program then “says” the text that is entered (in a quote box created with asterisks). The program will then print an ASCII fox. Below are two examples of the output from running <em>FoxSays</em> with the text the user enters underlined in red:




(Original ASCII fox art credit goes to Todd Vargo)

In your program, you will create two static methods:

<ol>

 <li>A static method called <em>theMessage()</em>, which does the following:

  <ol>

   <li>Prompts the user to enter text (Print out: “What does the fox say?”).</li>

   <li>Creates and uses a <em>Scanner</em> object and its <em>nextLine()</em> method to read input from the user through the command-line interface.</li>

   <li>Uses the String’s <em>length()</em> method to determine the message’s size (the total number of characters in the String the fox says)</li>

   <li>Uses <em>for-loops</em> to create the appropriate sized quotation box around the fox’s message (the *’s above and below the message).</li>

  </ol></li>

</ol>




<ol start="2">

 <li>A static method named <em>printFox()</em>, which should print out an ASCII fox:

  <ol>

   <li>Remember your escape sequences to print out quotes (“) and backslashes ().</li>

  </ol></li>

</ol>




Advice: Build this method in parts, compiling and running after each major addition to your code to check that the code does work as you expect. For example, you might first prompt the user to enter some text, then store the text as a string, and then directly print the text back. After that you might write <em>theMessage()</em> method and then, finally, add the necessary for loops.

<em> </em>

<em>File to submit: FoxSays.java </em>

<strong> </strong>

<h1>Marking</h1>

Your mark will be based on the following criteria:

<ul>

 <li>Your code <em>must compile and run</em>. It must prompt the user, read text input, and produce the expected output as described and shown above.</li>

</ul>




<ul>

 <li>Your code must conform to the requirements mentioned above (i.e., have <em>theMessage()</em> and<em> printFox()</em> methods, a <em>Scanner</em> object, <em>for-loops</em>, etc.).</li>

</ul>




<ul>

 <li>Your code must follow the guidelines outlined in Style_Guidelines.pdf, found through the Lectures &amp; Stuff link in the Lab Resources folder on connex.</li>

</ul>


