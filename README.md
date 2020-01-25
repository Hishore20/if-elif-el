# if-elif-el


Write a program asks the user to enter a exam score, and then prints the grade (A/B/C/D) that corresponds to the score.

If the score that the user entered is less than 0 or greater than 100, the program prints an error message.
Use the following grades
A grade >=85
B grade 70-85
C grade 50-70
D grade <50

Mandatory:

Use if and elif
Logic Test Case 1

Input (stdin)
85

Expected Output

A
Logic Test Case 2

Input (stdin)
78

Expected Output

B
Mandatory Test Cases

Test Case 1
if
Test Case 2
elif


a=int(input())
if (a>=85):
    print('A')
elif (a>=70 and a<85):
    print('B')
elif (a>=50 and a<70):
    print('C')
else:
      print('D')   

	
