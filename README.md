Download Link: https://assignmentchef.com/product/solved-605-201-introduction-to-programming-using-java-assignment-4
<br>
<ol>

 <li>Write a program that prompts the user to enter a month (1-12) and a year (e.g., 2012), and then displays a calendar for that month and year as illustrated below:</li>

</ol>

<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/07/211.png?w=980&amp;ssl=1" class="aligncenter lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" class="aligncenter" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2018/07/211.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>Your program must use the following methods:

<strong>Method                                                                               Description</strong>

void printMonthCalendar( int month, int year )      Displays a calendar like the one above for a specified month and year.

void printMonthHeader( int month, int year )         Displays the header information ( month, year, line separator, 3-character day names) for a calendar.

void printMonthBody( int month, int year )              Displays the days in the calendar associated with the corresponding days of the week.

String getMonthName( int month )                              Returns the name of the month for a specified month number (e.g., returns March for m=3).

int getStartDay( int month, int year )                           Returns the day of week  number (1=Monday, …, 7= Sunday) of the first day of month/year specified.

int getNumDaysInMonth( int month, int year)         Returns the number of days in a specified

month and year. Leap years are accounted for.

boolean isLeapYear( int year )                                        Returns true if the specified year is a leap year, and returns false otherwise.

Code for the getStartDay() method can be downloaded from the course website. You must write the code for the remaining methods. Be sure to clearly document your code and your methods.

<strong>605.201 Introduction to Programming Using Java</strong>

<h1>Assignment 4</h1>

Note constants of calender body rows is not considered an acceptable technique for this assignment.  The calender body rows must be calculated.

The part of the assignment counts for 90% of this assignment’s grade.

<ol start="2">

 <li>Write a program that prompts the user to specify a year (e.g., 2012) and then displays a calendar for each month in that year. You must reuse the methods from part one. You can do this by copying your first program to a new file then edit the new one.</li>

</ol>

The part of the assignment counts for 10% of this assignment’s grade.

Submit the source code and  screen shots of each program’s output in a zip file named as follows: Assignment3 followed by an underscore (_) followed by your first name initial, followed by your last name, followed by your course section number. For example, if your name is Jane Smith and you are in section 81 your zip file would be <em>Assignment3_jsmith81.zip</em>.