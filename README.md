# Find the maximum of a list of numbers
## Aim:
To write a program to find the maximum of a list of numbers.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
1.	Get the list of marks as input
2.	Use the sort() function or max() function or use the for loop to find the maximum mark.
3.	Return the maximum value
## Program:

i)	# To find the maximum of marks using the list method sort.
```Python
Program to mark the maximum of marks using the list method sort
Developed by: RITHIKA N
RegisterNumber: 23013374
'''
def max_marks(marks):
    marks.sort()
    return marks[-1]


```

ii)	# To find the maximum marks using the list method max().
```Python
Program to find the maximum marks using the list method max().
Developed by: RITHIKA N
RegisterNumber: 23013374
'''
def max_marks(marks):
    a=max(marks)
    return a



```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: RITHIKA N
RegisterNumber: 23013374
'''
def max_marks(list1):
    a=0
    for i in list1:
        if i>a:
            a=i
    return a



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/Rithikachezhian/FindMaximum/assets/145742406/6206657a-4380-4262-b1f8-8462b30dbc31)
![image](https://github.com/Rithikachezhian/FindMaximum/assets/145742406/6532c69f-7861-4c49-925d-80f501186220)
![Screenshot 2023-12-14 140911](https://github.com/Rithikachezhian/FindMaximum/assets/145742406/12b894a9-e4ae-4ab0-a961-17ff2f7020df)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
