# Word-Count
### NAME: AVINASH T
### REG NO: 212223230026
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import numpy as np
### Step 2: 
Enter the input values
### Step 3: 
Write python program for getting the word count from the contents of a file using command line arguments
### Step 4:  
Run the program
### Step 5: 
Input the values
### Step 6: 
End the program
## PROGRAM:
```C
#Program to find the number of words in a text file
#Developed by : AVINASH T
#Register number : 212223230026
count=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        count += len(word)
print("The number of words are in the file is ",count)
```
### OUTPUT:
![image](https://github.com/AVINASH05T/Word-Count/assets/151514286/836910d9-a2a7-4a13-85dd-d90ea7f23c54)
![image](https://github.com/AVINASH05T/Word-Count/assets/151514286/6cc068d3-87ae-43a0-99d6-bf832d0eb2cb)
## RESULT:
Thus the program is written to find the word count from a text.
