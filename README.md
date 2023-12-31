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

Then decleare count is equal to 0
 
### Step 3: 

read the file with python file name

### Step 4:  

Splitting the word

### Step 5: 

After splitting count the number of words in the line

### Step 6: 

In last statement give the print statement.


## PROGRAM:
```
#python program for getting the word count from the contents of a file using command line arguments.
#Developed by:SRISHANTH J
#Register number:212223240160
import sys
fp=open(sys.argv[0])
data=fp.read()
words=data.split()
print("no of words",len(words))
```
### OUTPUT:
<img width="609" alt="Screenshot 2023-12-31 185157" src="https://github.com/srishanth2006/command-line-arguments-to-count-word/assets/150319470/3e3db687-57f0-4da4-bf40-beffb91be985">



## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
