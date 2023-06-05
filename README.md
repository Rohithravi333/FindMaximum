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
![sort program](https://github.com/Rohithravi333/FindMaximum/assets/119394126/a683e2e8-bdad-48b4-a4be-a6a977d3e785)
![def](https://github.com/Rohithravi333/FindMaximum/assets/119394126/72f95243-70f3-4d0e-86bb-ef50f9d7b5a6)
![max](https://github.com/Rohithravi333/FindMaximum/assets/119394126/2b3f44fc-b5d7-42b7-b64c-ba5bb39dd7d1)
![Screenshot from 2023-01-14 09-07-28](https://github.com/Rohithravi333/FindMaximum/assets/119394126/0030e376-f09d-48b6-8db2-5d6b377daca2)
![bullitten program](https://github.com/Rohithravi333/FindMaximum/assets/119394126/d7e4ea4b-285f-4f01-a2aa-f66833bc6db5)



## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
