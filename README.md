# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
To write a python program for getting the word count from a text file.
### Step 2: 
 Open the required file by using the function "with"
### Step 3: 
Then use the laptop to assign the i value in the file
### Step 4:  
Using split function to spilt the words
### Step 5: 
Finding the given length of the words by using len() fuction.
### Step 6: 
Calling the function and Printing the number of words.
## PROGRAM:
```python
Program to count the no. of words in a file.
Developed by:NITHISH MD
Reg.no:23009587
'''
fname=input("Enter the file name:")
num_words=0
with open(fname,"r") as f:
  for line in f:
    words=line.split()
    num_words+=len(words)
  print("Number of words:",num_words)

```
### OUTPUT:
![293364581-b48e8e75-e480-466f-b3e0-f9af2b6a88ea](https://github.com/Mrnithishx/Word-count/assets/148201573/08b54a3f-6b6a-48ac-95a5-5d919b1d2805)

## RESULT:
Thus the program is written to find the word count from a text.
