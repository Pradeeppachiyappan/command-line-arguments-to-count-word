# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

 import sys

### Step 2:
Open file using open().

### Step 3:
Use for loop.

### Step 4:
Use len to count number of words.

## PROGRAM:
```
#program is developed: AJAY ASWIN
# REF.NO: 22009241
import sys
count= 0
with open(sys.argv[1],'r') as file:
    for line in file:
        word= line.split()
        count += len(word)
print("program is developed: AJAYASWIN.M")
print("word count in file = ",count)
```
### OUTPUT:



![o](https://user-images.githubusercontent.com/118679692/214778288-7fb40c58-2e65-436e-afab-471fdd26992d.jpeg)
![out1](https://user-images.githubusercontent.com/118679692/214777766-f012a5bc-3f48-4e49-a21b-b799a32e62f1.jpeg)
## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
