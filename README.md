# Student-Progress-Tracker
Applied-Artificial-Intelligence

Introduction:
Hours/Week is the number of hours the student has spent studying for his coursework. This variable has
three types:
1. low – that is between 0 - 10hrs
2. medium – this is between 20 - 40hrs
3. high – this is between 30 – 40hrs
Based on the hours/week that are spent on studying, the student is given a performance rating. Performance rating is of the following types:
1. Poor
2. Satisfactory 3. Good
4. Excellent
The performance of the student is based on the number of hours per week spent on studying and this value can be fuzzy.
The performance rating of the student decides his grade increment. If his performance is low, he gets no increment in his grades. However, if his performance is excellent, he gets a 20% increment in his grades.
Security:
For security purposes, the user will be asked for a username and password which are: admin and
adminpass. This ensures that someone who is not authorized does not access the data on this expert system.
Test Case:
Username:
hint: username is admin
admin
Password:
hint: password is adminpass
adminpass
Welcome to Student Progress Tracker, Admin!
Sr. No.
Hours/week
 
Performance Rating
Grade Increment
1.
Low
 
Poor
 
No increment in grades
2.
Low-medium
Satisfactory
5%
3.
Medium
 
Good
 
7%
4.
Medium-high
Good
 
10%
5.
High
 Excellent
20%
Enter student name:
Yoda
How many hours does the student study per week? (1/2/3)
1. 1-10 hours/week 2. 20-40 hours/week 3. 30-40 hours/week Enter your choice:
3 *************************************************
CONCLUSION
*************************************************
Yoda is rated excellent since the average time spent on studying is high.
rating is: FuzzyVariable -> rating [ 0.0, 100.0 ] percentage
Linguistic Expression -> ???
FuzzySet -> { 0/70 0.03/73.75 0.12/77.5 0.28/81.25 0.5/85 0.72/88.75 0.88/92.5 0.97/96.25 1/100 }
hour is: FuzzyVariable -> timespent per week [ 0.0, 40.0 ] hours/week
Linguistic Expression -> high
FuzzySet -> { 0/30 0.03/31.25 0.12/32.5 0.28/33.75 0.5/35 0.72/36.25 0.88/37.5 0.97/38.75 1/40 } Fuzzy Value: rating
Linguistic Value: excellent (*), ??? (+)
1.00
0.95
0.90
0.85
0.80
0.75
0.70
0.65
0.60
0.55
0.50
0.45
0.40
0.35
0.30
0.25
0.20
0.15
0.10
0.05 0.00+++++++++++++++++++++++++++++++++++++
|----|----|----|----|----|----|----|----|----|----|
0.00 20.00 40.00 60.00 80.00 100.00
Fuzzy Value: timespent per week Linguistic Value: high (*)
1.00 ** 0.95 * 0.90 *
++ +
+ +
+ +
+ +
+ +
+ +
+
0.85
0.80
0.75
0.70
0.65
0.60
0.55
0.50
0.45
0.40
0.35
0.30
0.25
0.20
0.15
0.10
0.05 0.00***************************************
* *
* *
*
* *
*
|----|----|----|----|----|----|----|----|----|----| 0.00 8.00 16.00 24.00 32.00
Fuzzy Value: timespent per week Linguistic Value: high (*)
40.00
1.00
0.95
0.90
0.85
0.80
0.75
0.70
0.65
0.60
0.55
0.50
0.45
0.40
0.35
0.30
0.25
0.20
0.15
0.10
0.05 0.00***************************************
|----|----|----|----|----|----|----|----|----|----|
0.00 8.00 16.00 24.00 32.00 40.00
**************************************** GRADE INCREMENT EVERY SEMESTER ****************************************
** *
* *
* *
*
*
* *
*
Yoda has the grade increment of 20% this semester. *************************************************
CONCLUSION
*************************************************
Yoda is rated good since the average time spent on studying is med-high.
rating is: FuzzyVariable -> rating [ 0.0, 100.0 ] percentage
Linguistic Expression -> ???
FuzzySet -> { 0/40 1/50 0/60 0/70 0.03/73.75 0.12/77.5 0.28/81.25 0.5/85 0.72/88.75 0.88/92.5 0.97/96.25 1/100 }
hour is: FuzzyVariable -> timespent per week [ 0.0, 40.0 ] hours/week
Linguistic Expression -> high
FuzzySet -> { 0/30 0.03/31.25 0.12/32.5 0.28/33.75 0.5/35 0.72/36.25 0.88/37.5 0.97/38.75 1/40 } Fuzzy Value: rating
Linguistic Value: good (*), ??? (+)
1.00
0.95
0.90
0.85
0.80
0.75
0.70
0.65
0.60
0.55
0.50
0.45
0.40
0.35
0.30
0.25
0.20
0.15
0.10
0.05 0.00+++++++++++++++++++++
1.00 0.95 0.90 0.85 0.80 0.75 0.70 0.65 0.60 0.55
* ** ** *
** ** *
* **
* **
***
+ ++ +
++
+
++
+
+ ++
+
+ +
+
0.00 20.00 40.00 60.00 80.00 100.00 Fuzzy Value: timespent per week
Linguistic Value: medium or high (*)
+ ++
+ +
+
+++++++************** |----|----|----|----|----|----|----|----|----|----|
0.50
0.45
0.40
0.35
0.30
0.25
0.20
0.15
0.10
0.05
0.00************** **
|----|----|----|----|----|----|----|----|----|----| 0.00 8.00 16.00 24.00 32.00
Fuzzy Value: timespent per week Linguistic Value: high (*)
* * *
* *
*
* ** * **
* **
1.00
0.95
0.90
0.85
0.80
0.75
0.70
0.65
0.60
0.55
0.50
0.45
0.40
0.35
0.30
0.25
0.20
0.15
0.10
0.05 0.00***************************************
|----|----|----|----|----|----|----|----|----|----|
0.00 8.00 16.00 24.00 32.00 40.00
**************************************** GRADE INCREMENT EVERY SEMESTER ****************************************
Yoda has the grade increment of 10% this semester.
How to run the program(Instructions):
1. Go to run configurations of test2.clp.
2. Set the following:
i) Name – test2.clp
** *
* *
* *
*
*
* *
*
40.00
ii) Jess Script – src/test2.clp
iii) Jess main class - nrc.fuzzy.jess.FuzzyConsole
3. Apply and run
4. Output appears in a console.
