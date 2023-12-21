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
```
''' 
Program to mark the maximum of marks using the list method sort
Developed by: guntur shaik mohammad shahil
RegisterNumber: 23011002
'''
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large

```

ii)	# To find the maximum marks using the list method max().
```
''' 
Program to find the maximum marks using the list method max().
Developed by: guntur shaik mohammad shahil
RegisterNumber:23011002
'''
def max_marks(marks):
    max_marks=max(marks)
    return max_marks
    
```

iii) # To find the maximum marks without using builtin functions.
```
''' 
Program to the maximum marks without using builtin functions.
Developed by: guntur shaik mohammad shahil
RegisterNumber: 23009906
'''
def max_marks(list1):
    max_numbers=0
    for num in list1[1:]:
        if num>max_numbers:
            max_numbers=num
    return max_numbers

```
# Sample Input and Output
![output](./img/max_marks1.jpg) 
![image](https://github.com/mohammadshahil09/FindMaximum/assets/145742840/68ab4820-5b4c-49d7-aed4-08f9c94b987f)
![image](https://github.com/mohammadshahil09/FindMaximum/assets/145742840/ce1c08c2-57df-41c0-8d92-4ff0bab96fcc)



# Output:
![image](https://github.com/mohammadshahil09/FindMaximum/assets/145742840/c96800b2-45ec-49d0-9ac3-f0e962e98584)
![image](https://github.com/mohammadshahil09/FindMaximum/assets/145742840/364f0a4b-f7f4-4ac2-887a-dcb9d4dedd94)
![image](https://github.com/mohammadshahil09/FindMaximum/assets/145742840/d086d556-c72e-4b9d-8a01-3905f72a7a7b)



# Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
