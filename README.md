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
Developed by: Mirudhula D
RegisterNumber: 21002651
'''
def max_marks(marks):
    marks.sort()
    max=marks[-1]
    return max


```

ii)	# To find the maximum marks using the list method max().
```Python
''' 
Program to find the maximum marks using the list method max().
Developed by: Mirudhula D
RegisterNumber: 21002651
'''
def max_marks(marks):
    max=0
    for i in marks:
        if max<i:
            max=i
    return max


```

iii) # To find the maximum marks without using builtin functions.
```Python
''' 
Program to the maximum marks without using builtin functions.
Developed by: Mirudhula D
RegisterNumber: 21002651
'''
def max_marks(marks):
    a=max(marks)
    return a


```
## Sample Input and Output
![maxnum1](https://user-images.githubusercontent.com/94828147/153796743-86bbda61-061d-4c5f-be30-19fd60b04f36.png)
![maxnum2](https://user-images.githubusercontent.com/94828147/153796763-55163346-2258-4f34-81e1-3f196ffd4312.png)
![maxnum3](https://user-images.githubusercontent.com/94828147/153796784-50a69970-b7f7-4a1b-86f6-e9bfa8e97c8b.png)
![maxnum4](https://user-images.githubusercontent.com/94828147/153796801-e0a62033-aeff-452f-86e9-805383f6c75a.png)
![maxnum5](https://user-images.githubusercontent.com/94828147/153796825-7ec54115-5d81-45ce-bc19-9578cb1a6992.png)
![maxnum6](https://user-images.githubusercontent.com/94828147/153796841-08a2b72b-36fc-4da2-b84f-5982de9bc123.png)

## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
