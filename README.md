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
initially make count = 0

### Step 3: 
open the content file using command line arguments.

### Step 4:  
by using for loop name the function as "line"

### Step 5: 
split the line using .split

### Step 6: 
split the line using .split

## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: BALAMURUGAN B
Register Number: 212222230016

import sys
fp=open(sys.argv[1],'r')
count=0
for line in fp:
    words=line.split()
    count+=len(words)
print("Number of words in a file",count)
```
### OUTPUT:
![5bi](https://github.com/BALA291/command-line-arguments-to-count-word/assets/120717501/dbbcf242-3357-494a-aaf1-8fec645a7ac6)
![5bii](https://github.com/BALA291/command-line-arguments-to-count-word/assets/120717501/928ae58b-8ca2-446b-9c15-9c38a2c77cce)
![5biii](https://github.com/BALA291/command-line-arguments-to-count-word/assets/120717501/ff48ca3c-00cd-47d5-a3ad-9a8f543bc793)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
