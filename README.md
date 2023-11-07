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
Developed by: jeevanesh
RegisterNumber: 23013802
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max
```

ii)	# To find the maximum marks using the list method max().
```Python 
Program to find the maximum marks using the list method max().
Developed by: jeevanesh
RegisterNumber: 23013802
'''
def max_marks(marks):
    max_value=max(marks)
    return max_value    
```

iii) # To find the maximum marks without using builtin functions.
```Python
Program to the maximum marks without using builtin functions.
Developed by: jeevanesh
RegisterNumber: 23013802
'''
def max_marks(list1):
    max= list1[0]
    for i in list1:
        if i>max:
            max=i
    return max        
```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
![image](https://github.com/plotswag/FindMaximum/assets/145822344/9045018f-84a6-4e7a-a91c-63fa0cd44bc7)
![image](https://github.com/plotswag/FindMaximum/assets/145822344/c26f8f2b-238a-4930-9c1c-41f54186311c)
![image](https://github.com/plotswag/FindMaximum/assets/145822344/f151251c-3576-456a-bd42-8f217600d0df)
## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
