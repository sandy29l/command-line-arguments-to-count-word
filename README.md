# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import sys module
### Step 2: 
 Open the file with sys.argv[1]
### Step 3: 
Use the for loop to select the content in file
### Step 4:  
Use split function to to separate the file content into words or strings
### Step 5: 
Count the length of the words using len
### Step 6: 
Print the number of words
## PROGRAM:
```
Program for getting the word count from the contents of a file using command line arguments
Developed by: Santhosh L
RegisterNumber: 212222100046

import sys
fp=open(sys.argv[1], 'r')
count=0
for line in fp:
    list1=line.split()
    count+=len(list1)
print("No of words in a file",count)
```
### OUTPUT:

![ouput 3](https://github.com/sandy29l/command-line-arguments-to-count-word/assets/123359969/a39ff177-516e-4953-b86a-1b6fc4e93201)
![output1](https://github.com/sandy29l/command-line-arguments-to-count-word/assets/123359969/b8b9f3d9-b539-4bb4-bf48-8488f70525b8)
![output 2](https://github.com/sandy29l/command-line-arguments-to-count-word/assets/123359969/32935bd6-843a-4785-8053-d9896e08e9e4)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
