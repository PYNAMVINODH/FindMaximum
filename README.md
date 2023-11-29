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
Developed by: PYNAM VINODH
RegisterNumber: 23004069


'''
def max_marks(marks):
    #Write your code here
    marks.sort()
    large=marks[-1]
    return large
    
 


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: PYNAM VINODH
RegisterNumber: 23004069
'''
def max_marks(marks):
    # write your code here
    large=max(marks)
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python

''' 
Program to the maximum marks without using builtin functions.
Developed by: PYNAM VINODH
RegisterNumber: 23004069
'''
def max_marks(list1):
    # write your code here
    max=list1[0]
    for i in list1:
        if i>max:
            max=i
    return max

```
## Sample Input and Output
i) # To find the maximum of marks using the list method sort.
![image](https://github.com/PYNAMVINODH/FindMaximum/assets/145742678/f25c00a0-f981-4902-a43b-54369799a3d8)
ii) # To find the maximum marks using the list method max().
![image](https://github.com/PYNAMVINODH/FindMaximum/assets/145742678/f972fa03-adac-474b-88a9-ca78becc3eba)
iii) # To find the maximum marks without using builtin functions.
![image](https://github.com/PYNAMVINODH/FindMaximum/assets/145742678/ed1fda41-f60e-46a6-b3f8-32ef6157e7f4)


## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
