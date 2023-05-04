Download Link: https://assignmentchef.com/product/solved-cse-222-505-homework-04
<br>
For the questions 1-4, prepare a pdf document with the same font as the Report Format. For the last question prepare a Java project with a main class. Submit your work as studentID.zip




<ol>

 <li>Given a single linked list of integers, we want to find the maximum length sorted sublist in this list. For example for the list L= {1, 9, 2, 7, 20, 13} the returned list should be S = {2, 7, 20}.</li>

</ol>




<ol>

 <li>Write an iterative function which performs this task. Analyze its complexity.</li>

 <li>Write a recursive function for the same purpose. Analyze its complexity by using both the Master theorem and induction.</li>

</ol>







<ol start="2">

 <li>Describe and analyze a Θ (n) time  algorithm  that  given  a  sorted  array searches two numbers in the array whose sum is exactly x.</li>

 <li>Calculate the running time of the code snippet below</li>

</ol>

for (i=2*n; i&gt;=1; i=i-1) for (j=1; j&lt;=i; j=j+1) for (k=1; k&lt;=j; k=k*3) print(“hello”)




<ol start="4">

 <li>Write a recurrence relation for the following function and analyze its time complexity T(n).</li>

</ol>







<ol start="5">

 <li>It’s the year 2019, and the Göktürk 3 satellite is in orbit. You work as a data analyst for the Turkish Space Agency. The satellite transmits data as 2D arrays (not necessarily square) of non negative integers. You are tasked with coding an iterator class for these data that will traverse a given 2D array spirally clockwise starting at the top left element.</li>

</ol>




1 2 3 4

5 6 7 8

9 10 11 12

Example: if the data is 13 14 15 16




the iterator should iterate it in the order: 1 2 3 4 8 12 16 15 14 13 9 5 6 7 11 10. Code in java this iterator recursively, and provide a main class showing it in action. Do not implement its remove method (final exam question from 2 years ago of BIL443; it was worth 15 points at the time).