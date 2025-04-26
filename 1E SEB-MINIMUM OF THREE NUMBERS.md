# Experiment No: 1e – SEB-Percentage and class of students.

## AIM  
To write a python program to compute and print the percentage and class of students. 

## ALGORITHM  
1. Begin the program.
2. Take the marks as input from the user.
3. Calculate the percentage by dividing the marks by 6.
4. If the percentage is greater than or equal to 70:
   a. Display the percentage.
   b. Display "First Class with Distinction".
5. Else if the percentage is between 60 and 70 (60 ≤ percentage < 70):
   a. Display the percentage.
   b. Display "First Class".
6. Else if the percentage is between 50 and 60 (50 ≤ percentage < 60):
   a. Display the percentage.
   b. Display "Second Class".
7. Else if the percentage is between 35 and 50 (35 ≤ percentage < 50):
   a. Display the percentage.
   b. Display "Passed".
8. Else:
   a. Display the percentage.
   b. Display "Failed".
9. Terminate the program.

## PROGRAM
      mark=int(input())
      per=mark/6;
      if(per>=70):
          print("You have scored ",end='')
          print("%.2f"%per,end='')
          print("% of marks\nFirst Class with Distinction");
      elif(per>=60 and per<70):
          print("You have scored ",end='')
          print("%.2f"%per,end='')
          print("% of marks\nFirst Class")
      elif(per>=50 and per<60):
          print("You have scored ",end='')
          print("%.2f"%per,end='')
          print("% of marks\nSecond Class")
      elif(per>=35 and per<50):
          print("You have scored ",end='')
          print("%.2f"%per,end='')
          print("% of marks\nPassed")
      else:
          print("You have scored ",end='')
          print("%.2f"%per,end='')
          print("% of marks\nFailed")

## OUTPUT
![image](https://github.com/user-attachments/assets/1c00e0df-9c38-4d81-9343-2a1bd1765c1f)

## RESULT
Thus, the python program to print the percentage and class of students is implemented and executed successfully.
