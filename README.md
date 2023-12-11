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

# To find the maximum of marks using the list method sort.
```
Program to mark the maximum of marks using the list method sort
Developed by: Narendran.k
RegisterNumber: 23013500
'''
def max_marks(marks):
    return(max(marks))
```

# To find the maximum marks using the list method max().
```
Program to find the maximum marks using the list method max().
Developed by: Narendran.k
RegisterNumber: 23013500
'''
def max_marks(marks):
    return(max(marks))
```

# To find the maximum marks without using builtin functions.
```
Program to the maximum marks without using builtin functions.
Developed by: Narendran.k
RegisterNumber: 23013500
'''
def max_marks(list1):
    i=list1[0]
    for a in list1:
        if a>i:
            i=a
        else:
            i=i
    return(i)
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![Output1](https://github.com/Narendran-sec/FindMaximum/assets/147473131/62b93fce-9771-497f-a311-b9f288ad0c77)
![Output2](https://github.com/Narendran-sec/FindMaximum/assets/147473131/6ef9be5d-a41f-4b06-aca4-8f1a098f7335)
![Output3](https://github.com/Narendran-sec/FindMaximum/assets/147473131/171fd9bf-1fbc-4148-a41d-963990a3f68d)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
