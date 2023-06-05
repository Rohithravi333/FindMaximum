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
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large
    


```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large


```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(list1):
    temp=0
    for i in list1:
        if temp<i:
            temp=i
    return temp        


```



## Output:
![max_marks1](https://github.com/Rohithravi333/FindMaximum/assets/119394126/3ee8e0e7-1d33-49cf-8bc1-dbe7697d9ac7)
![c1 c](https://github.com/Rohithravi333/FindMaximum/assets/119394126/f0b658d7-833f-4ca9-aa44-25fd32797f29)





## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
