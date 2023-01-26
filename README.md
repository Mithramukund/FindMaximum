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
    marks.sort() # sorts the list in ascending order
    max_mark = marks[-1] # gets the last element (highest mark)
    return max_mark

marks = [70, 80, 90, 75, 85]

maximum_mark = max_marks(marks)
```

ii)	# To find the maximum marks using the list method max().
```Python
def max_marks(marks):
    large = max(marks)
    return large
```

iii) # To find the maximum marks without using builtin functions.
```Python
def max_marks(marks):
    large = max(marks)
    return large
```
## Sample Input and Output
![Screenshot_20230126_050347](https://user-images.githubusercontent.com/121608770/214825819-911fdbf2-747b-431c-8e93-9826d20b9d0a.png)



## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
