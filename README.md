Download Link: https://assignmentchef.com/product/solved-data51100-assignment-5-data-preparations-and-statistics
<br>
<span class="kksr-muted">Rate this product</span>

Assignment 5 – Data Preparations and Statistics

The file cps.csv (attached) contains school profile information for Chicago Public Schools. Your program will derive some data from it and then generate some statistical information.

Requirements

You are to create a program in Python that performs the following:1. Loads the cps.csv file (assume it’s in the current directory) and create a DataFrame object from it.

on the data contained in the cps.csv file, generates a dataframe with the following information:

<ol start="2">

 <li>Short_Name</li>

 <li>Is_High_School</li>

 <li>Zip</li>

 <li>Student_Count_Total</li>

 <li>College_Enrollment_Rate_School</li>

 <li>Lowest Grade Offered (derived from Grades_Offered_All column)</li>

 <li>Highest Grade Offered (derived from Grades_Offered_All column)</li>

 <li>Starting Hour (derived from School_Hours column)</li>

</ol>

The values for a-f are based on existing columns in the data. For g-i, you will need to generate new columns which derives information from existing ones.

Replace the missing numeric values with the mean for that column. Display the first 10 rows of this dataframe.

3. Displays the following information:

<ol>

 <li>Mean and standard deviation of College Enrollment Rate for High Schools</li>

 <li>Mean and standard deviation of Student_Count_Total for non-High Schools</li>

 <li>Distribution of starting hours for all schools</li>

 <li>Number of schools outside of the Loop Neighborhood (i.e., outside of zip codes 60601, 60602,60603, 60604, 60605, 60606, 60607, and 60616)</li>

</ol>

Additional Requirements

<ol>

 <li>The name of your source code file should be DataStats.py. All your code should be within a single file.</li>

 <li>You need to use the pandas DataFrame object for storing data.</li>

 <li>Your code should follow good coding practices, including good use of whitespace and use of both inline and block comments.</li>

 <li>You need to use meaningful identifier names that conform to standard naming conventions.</li>

 <li>At the top of each file, you need to put in a block comment with the following information: your name,date, course name, semester, and assignment name.</li>

</ol>

What to Turn InYou will turn in the single DataStats.py file as well as a screenshot of your output(s) using BlackBoard.

Sample Program Output

CORRECTION: