                                                            INSTRUCTIONS: 
1.	The project has to be done on induvial bases. 

The Project Description: 
A school maintains academic record of its students (of a class) in different arrays. The information stored is: 
1.	Roll Number (in an integer array) 
2.	Midterm Marks (in a float array) 
3.	Final Marks (in a float array) 
4.	Class of a student e.g., Class 1, Class 2, Class 3 (in an integer array)  
5.	The Grades based on final marks (in char array)  
a.	Final Marks less than 50 – F 
b.	Final Marks: 50 to 59 (both inclusive) – D  
c.	Final Marks: 60 to 72 (both inclusive) – C 
d.	Final Marks: 73 to 85 (both inclusive) – B 
e.	Final Marks: 86 and above – A   
 
This program can display data from the existing student record. At the start of program, a menu will be displayed. The program will continue to work until e or E is entered. Error message will be displayed if any number (or a character) other than the given option is entered. Each array must have a size 100 and for the sake of my convenience, the arrays should be populated with exactly 50 student entries. The roll numbers must be unique – you have to take care of this. The example is shown below: 
 
Roll 
Number 	 
  
  
 	Midterm 
(50 marks) 	 
  
  
 	Final (100 marks) 	 
  
  
 	Class 	 
  
  
 	Grade 
25 		10.5 		55 		6 		D 
66 		36 		75.5 		6 		B 
45 		8 		55 		7 		D 
. 		. 		. 		. 		. 
. 		. 		. 		. 		. 
. 		. 		. 		. 		. 
 
The main menu must be the following (the comments written in the menu below are for your understanding and SHOULD not be displayed as such): 
1.	Sort and display all the records roll number wise in ascending order.  /*When this option is selected, the output should be: 
 
Roll No: 25   Midterm Marks: 10.5   Final Marks: 55      Class: 6   Grade: D 
Roll No: 45   Midterm Marks: 8        Final Marks: 55      Class: 7   Grade: D 
Roll No: 66   Midterm Marks: 36      Final Marks: 75.5   Class: 6   Grade: B 
 	. 	 	. 	  	 	 . 	 	          .  	   . 
 	. 	 	. 	 	 	 . 	 	          .  	   . 
. 	 	. 	 	 	 . 	 	          .   	outputs for options 2-8 must be similar to option 1/* 	   . 
2.	Sort and display all the records roll number wise in descending order.  
3.	Sort and display all records in ascending order based on marks in Midterm 
4.	Sort and display all records in descending order based on marks in Midterm 
5.	Sort and display all records in ascending order based on marks in Final 
6.	Sort and display all records in descending order based on marks in Final 
7.	Sort and display all records in ascending order based on Grade 
8.	 Sort and display all records in descending order based on Grade 
9.	 Add a new entry of a student.  
/*Assuming that the arrays got sorted after option 1 was selected, the new student entry which got added is shown below. Addition must be done on the next available index. You must ensure that the arrays are not full. In this option you will also make sure that the roll number that is being entered in unique: 
 
Roll 
Number 	 
 
 
 
 
 
 	Midterm 
(50 marks) 	 
 
 
 
 
 
 	Final (100 marks) 	 
 
 
 
 
 
 	Class 	 
 
 
 
 
 
 	Grade 
25 		10.5 		55 		6 		D 
45 		8 		55 		7 		D 
66 		36 		75.5 		6 		B 
40 		25 		87.5 		8 		A 
. 		. 		. 		. 		. 
. 		. 		. 		. 		. 
. 		. 		. 		. 		. 
 
*/ 
10.	Delete a student record based on his roll number.  
/*In this option, the user will enter a roll number and the whole data related to it must be deleted. The entries must be shifted so that there is no space in between any entry. Assuming that the user enters 66, the arrays after deletion are shown below: 
 
Roll 
Number 	 
 
  
 
 
 	Midterm 
(50 marks) 	 
 
  
 
 
 	Final (100 marks) 	 
 
  
 
 
 	Class 	 
 
  
 
 
 	Grade 
25 		10.5 		55 		6 		D 
45 		8 		55 		7 		D 
40 		25 		87.5 		8 		A 
. 		. 		. 		. 		. 
. 		. 		. 		. 		. 
. 		. 		. 		. 		. 
 	*/ 
11.	Display record of all the students greater than X marks in final exam (in descending order with respect to marks obtained in final exam). The value of X will be entered by the user.  
12.	Display record of all the students greater than X marks in final exam (in ascending order with respect to marks obtained in final exam). The value of X will be entered by the user.  
13.	Display record of all the students less than or equal to X marks in final exam (in descending order with respect to marks obtained in final exam). The value of X will be entered by the user.  
14.	Display record of all the students less than or equal to X marks in final exam (in ascending order with respect to marks obtained in final exam). The value of X will be entered by the user.  
15.	Display record of all the students greater than X grade (in descending order with respect to grade). The value of X (character) will be entered by the user.  
16.	Display record of all the students greater than X grade (in ascending order with respect to grade). The value of X (character) will be entered by the user.  
17.	Display record of all the students less than or equal to X grade (in descending order with respect to grade). The value of X (character) will be entered by the user. 
18.	Display record of all the students less than or equal to X grade (in ascending order with respect to grade). The value of X (character) will be entered by the user. 
