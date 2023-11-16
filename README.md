# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module.
### Step 2: 
 Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]
### Step 3: 
Read file using read() method.
### Step 4:  
Use split() method to split the file content into words.
### Step 5: 
Use len() to find the total words.
### Step 6: 
Run the program to determine the number of words in the file created.
## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: LINGESWARAN K
RegisterNumber: 212222110022

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```
### OUTPUT:
![image](https://github.com/Lingeswaran04/command-line-arguments-to-count-word/assets/119103865/0bfa4294-64b0-4cd1-b934-c5075282fc7a)

![image](https://github.com/Lingeswaran04/command-line-arguments-to-count-word/assets/119103865/3016bfc5-b9d0-45c6-9e72-57d331b6989e)

![image](https://github.com/Lingeswaran04/command-line-arguments-to-count-word/assets/119103865/2792c3d7-3959-4b1f-bdf1-7d3550756240)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
