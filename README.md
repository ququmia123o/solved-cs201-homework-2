Download Link: https://assignmentchef.com/product/solved-cs201-homework-2
<br>
In this homework, you will analyze and compare algorithmic complexity of four different solutions for the

<strong><em>Maximum Subsequence Sum Problem</em></strong>. For that, first read Section 2.4.3 (Solutions for the Maximum Subsequence Sum Problem) from the handout and study each of these four solutions. Be sure that you understand how the upper bounds are found for the running time of each solution. Then, implement these solutions in C++. Note that you may use the codes provided in the handout.

Next, write a driver (main) function that generates an array that contains integers and calls each of these solutions with that array as input. Run each solution on a computer and record execution times when different input sizes are used. You are expected to try many different input sizes, both small inputs and very large inputs (as large as thousands to millions depending on the solution), and observe the effects of different growth rates.

In this assignment,

<ol>

 <li>Use your results to generate a comparison table and a plot of running time (y-axis) versus the input size <em>N</em> (x-axis). In particular, you are expected to produce a table and a plot as in Figure 2.2 and Figure 2.3 of the handout, respectively. In the table, each row corresponds to an input size and each column holds the running times of a specific solution.</li>

 <li>Plot the expected growth rates obtained from the theoretical analysis (as given for each solution) by using the same <em>N</em> values that you used in obtaining your results. Compare the expected growth rates and the obtained results, and discuss your observations in a paragraph.</li>

 <li>Provide the specifications of the computer you used to obtain these execution times. You can use any computer with any operating system for this assignment.</li>

</ol>

You can use the following code segment to compute the execution time of a code block. For these operations, you must include the <strong><em>chrono</em></strong> header file.

<table width="657">

 <tbody>

  <tr>

   <td width="657"> // Declare necessary variablesstd::chrono::time_point&lt; std::chrono::system_clock &gt; startTime;   std::chrono::duration&lt; double, milli &gt; elapsedTime;// Store the starting timestartTime = std::chrono::system_clock::now();// Code block   …// Compute the number of milliseconds that passed since the starting time   elapsedTime = std::chrono::system_clock::now() – startTime;cout &lt;&lt; “Execution took ” &lt;&lt; elapsedTime.count() &lt;&lt; ” milliseconds.” &lt;&lt; endl;</td>

  </tr>

 </tbody>

</table>

1

<strong>NOTES ABOUT SUBMISSION:</strong>

<ol>

 <li>This assignment is due by 23:55 on Tuesday, April 16, 2019. You should upload your homework to the upload link on Moodle before the deadline. This upload link will be available between April 5th and 19th. No hardcopy submission is needed. The standard rules about late homework submissions apply. Please see the course web page for further discussion of the late homework policy as well as<u> academic integrity</u>.</li>

</ol>




<ol start="2">

 <li>In this assignment, you must submit a report (as a pdf file) that contains all information requested above (plots, tables, computer specification, discussion) and a cpp file that contains the main function that you used as the driver in your simulations as well as the solution functions in a single archive file.</li>

 <li>This homework will be graded by your TA Furkan Hüseyin (furkan.huseyin at bilkent edu tr). Thus, you may ask your homework related questions directly to him.</li>

</ol>