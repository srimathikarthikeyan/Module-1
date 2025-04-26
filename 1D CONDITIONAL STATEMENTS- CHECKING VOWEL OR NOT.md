## Experiment No: 1d – Conditional Statements- Checking leap year or not

## AIM  
To Write a Python program to check whether the given year is a leap year or not.

## ALGORITHM  
1. Begin the program.  
2. Take the year as input from the user
3. Check if the year is divisible by 4
4. If divisible by 4, then check:
   i. If the year is divisible by 100, then check:
       a. If the year is divisible by 400, then it is a leap year.
       b. Otherwise, it is NOT a leap year.
   ii. If the year is NOT divisible by 100, then it is a leap year.
5. If the year is NOT divisible by 4, then it is NOT a leap year.
6. Display the result.
7. Terminate the program.

## PROGRAM
    year = int(input())
    if(year%4==0):
        if(year%100==0):
            if(year%400==0):
                print("Given year",year,"is a leap year")
            else:
                print("Given year",year,"is not a leap year")
        else:
            print("Given year",year,"is a leap year")
    else:
        print("Given year",year,"is not a leap year")

## OUTPUT

![image](https://github.com/user-attachments/assets/4e13ff02-8418-4469-9076-da24d9278c73)

## RESULT
Thus, the python program to check whether the given year is leap year or not is implemented and executed successfully.
