# Word-Count
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
program to find the number of words in a text file
Developed by : K.HEMANATH
Register number : 212223100012

num=0
with open("story.txt","r") as f1:
    for i in f1:
        word=i.split()
        num += len(word)
print("The number of words are in the file is ",num)
### OUTPUT:
![output](https://github.com/Hemanath08/Word-Count/assets/151807176/33061956-072e-45ad-8d5d-a70e9bc7cd75)

## RESULT:
Thus the program is written to find the word count from a text.
