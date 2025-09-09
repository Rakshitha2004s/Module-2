# Exp.No:2d LOOPING PATTERNS - PRINTING PATTERN
# AIM
To write a Python program to print a pyramid pattern of numbers based on the number of rows entered by the user.

# ALGORITHM
Begin the program. Read the number of rows a from the user using input() and convert it to an integer. Use a for loop that runs from i = 1 to a (inclusive) to handle the number of rows. Inside the loop, use a nested for loop that runs from j = 1 to i (inclusive) to print numbers in each row. Print each number j followed by a space, and keep the output on the same line using end=" ". After the inner loop ends, move to the next line using print(end="\n"). Repeat steps 4–6 until the pyramid is printed. Terminate the program.

# PROGRAM
212222060245-Singamala Rakshitha
~~~
n=int(input())
for i in range(1,n+1):
    for j in range(1,i+1):
        print(j,end=' ')
    print('')
~~~
# OUTPUT
<img width="1199" height="567" alt="image" src="https://github.com/user-attachments/assets/ea83fa45-9401-4450-8cba-7ec3c6b46078" />

# RESULT
Thus the program to print a pyramid pattern of numbers based on the number of rows entered by the user has been implemented and executed successfully.
