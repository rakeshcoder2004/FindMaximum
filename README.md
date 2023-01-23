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

~~~py
def max_marks(marks):
    marks.sort()
    large = marks[-1]
    return large
~~~

~~~py
def max_marks(marks):
    large = max(marks)
    return large
~~~


~~~py
def max_marks(list1):
    max = list1[0]
    for i in list1:
        if i > max:
            max = i
    return max
~~~



## Sample Input and Output
![output](/max%20mark.png)

![output2](/max%203.png)

![output 3](/max4.png)

## Output:

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.