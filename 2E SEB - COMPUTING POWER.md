# Exp.No:2e SEB - SUM OF ODD NUMBER SERIES
# AIM
To write a Python program to calculate the sum of the odd number series from 1 to N using a loop.

# ALGORITHM
Start the program. Read a number num from the user using input(). Convert the input to an integer using int(). Initialize a variable sum to 0 to store the total sum. Loop from i = 1 to num (inclusive): Check if i is odd using i % 2 != 0. If true, add i to sum. After the loop, print the result in the format: "The sum of the series = " End the program.

# PROGRAM
212222060245-Singamala Rakshitha
~~~
num=int(input())
sum=0
for i in range(1,num+1):
  if(i%2!=0):
  sum+=i
print(f"The sum of the series = {sum}")
~~~
# OUTPUT
<img width="1199" height="360" alt="image" src="https://github.com/user-attachments/assets/6d48b1e5-9a98-4a86-bd13-1dab603f352e" />

# RESULT
Thus the program to calculate the sum of the odd number series from 1 to N using a loop has been implemented and executed successfully.
