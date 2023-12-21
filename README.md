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
''' 
Program to mark the maximum of marks using the list method sort
Developed by: AKASH KUMAR M.
RegisterNumber: 212223230010
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

ii) # To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: AKASH KUMAR M.
RegisterNumber: 212223230010 
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: AKASH KUMAR M.
RegisterNumber: 212223230010
'''
def max_marks(list1):
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max


```
## Sample Input and Output
![output](https://github.com/akash7812/FindMaximum/assets/146819826/7cc2722a-67e8-4de9-b5a3-5d0c35fb3f0a)

![output](https://github.com/akash7812/FindMaximum/assets/146819826/fe7858b7-5f33-4a3a-9474-e3022d412e84)


## Output:
![output](https://github.com/akash7812/FindMaximum/assets/146819826/4404cc51-0351-4e0a-a5df-80493c7264e0)

![output]![maxoutput](https://github.com/akash7812/FindMaximum/assets/146819826/9d2c8578-f57c-4aa3-a35a-9c4b82b2a215)

![output]![functionoutput](https://github.com/akash7812/FindMaximum/assets/146819826/2f8e3d7e-5b65-468f-b1d9-51b51edef81b)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
