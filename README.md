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
#Program to mark the maximum of marks using the list method sort
#Developed by: Sanjay Ragavendar M K
#RegisterNumber: 22009286

def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
```

ii)	# To find the maximum marks using the list method max().
```Python
#Program to find the maximum marks using the list method max().
#Developed by: Sanjay Ragavendar M K
#RegisterNumber: 22009286

def max_marks(marks):
    m=max(marks)
    return m
```

iii) # To find the maximum marks without using builtin functions.
```Python
#Program to the maximum marks without using builtin functions.
#Developed by: Sanjay Ragavendar M K 
#RegisterNumber: 22009286

def max_marks(list1):
    large = list1[0]
    for i in list1:
        if large<i:
            large=i
    return large
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
### (i)
![image](https://user-images.githubusercontent.com/91368803/215312243-a5c28cff-977e-45dd-ad30-a3a2a0dbc0ae.png)
### (ii)
![image](https://user-images.githubusercontent.com/91368803/215312258-c7fb5a21-b65f-42b7-9501-80eeac42e353.png)
### (iii)
![image](https://user-images.githubusercontent.com/91368803/215312313-f3bc37b3-3d8c-4810-a454-16aa64e4bb15.png)


## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
