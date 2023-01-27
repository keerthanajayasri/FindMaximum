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
```
Developed by:keerthana jayasri s k
Register Number:22006582
```
i)	# To find the maximum of marks using the list method sort.
```
def max_marks(list1):
    max_mark=0
    for i in list1:
        if i>max_mark:
            max_mark=i
    return max_mark





```

ii)	# To find the maximum marks using the list method max().
```

def max_marks(marks):
    a=max(marks)
    return a


```

iii) # To find the maximum marks without using builtin functions.
```def max_marks(marks):
    marks.sort()
    large=marks[-1]
    return large



```
## Sample Input and Output
![output](./img/max_marks1.jpg) 

## Output:
 
#### i)
![image](https://user-images.githubusercontent.com/121163440/215132000-6c97bfac-325f-44e9-9586-6b5fbae022e0.png)

#### ii)
![image](https://user-images.githubusercontent.com/121163440/215132081-8d353fea-219a-4d0d-9ef7-8288d4656e89.png)

#### iii)
![image](https://user-images.githubusercontent.com/121163440/215132179-8fc69f49-bf80-414b-823a-8958a14e9c9a.png)

## Result:
Thus the program to find the maximum of given numbers from the list is written and verified using python programming.
