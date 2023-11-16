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
import sys
fp= open(sys.argv[1])
data=fp.read()
words=data.split()
print("Total Words:",len(words))
```
### OUTPUT:
![image](https://github.com/Lingeswaran04/command-line-arguments-to-count-word/assets/119103865/283dbe57-ccba-4a62-af42-cc8c0ad62d1e)



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
