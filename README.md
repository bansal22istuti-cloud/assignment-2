## Assignment-2
this repository contains two task each for the assignment 2 of tutedude python program
## Task 1
this task aims to get an integer input from the user and check whether the number is even or odd using an if-else statement.

## Program of task 1

[ass2 task1.py](https://github.com/user-attachments/files/24259095/ass2.task1.py)

num=int(input("enter a number:"))
if num%2==0:
    print(num,"is an even number")
else:
    print(num,"is an odd number")

## Explanation of task 1 program


here variable num store user input of the number for which the user wants to find whether it is even or odd.
the way to determine if the number is odd or even is by dividing the number by 2 and if it is completely divisible that is the remainder is 0 then it is an even number, oterwise it is a odd number and this mechanism is applied through if else statement

## Task 2
this task to use a for loop to iterate over numbers from 1 to 50 and to Calculate the sum of all integers in this range and to display the final sum.


##  Program of task 2
[ass2task2.py](https://github.com/user-attachments/files/24262295/ass2task2.py)


total=0
for i in range(1,51):
    total=total+i
print("the sum of numbers from 1 to 50 is:",total)
input("press enter to exit")


## Explanation of task 2 program
here variable total stores a starting value which is 0.
in the for loop, the iterated value increase by 1 and the new total becomes the starting total plus iterated value. the loop runs till the final value set in the range and then the result is printed.

## Status
it has been verified before submission that the program runs successfully.



