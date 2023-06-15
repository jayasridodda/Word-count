# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:

Get the input as file name from the user.
### Step 2:

assign number of words = 0
### Step 3:

open file and read it.
### Step 4:

split the words separately by using split(
### Step 5:

calculate the sum of the words in file
### Step 6:

Print the number of words.

## PROGRAM:
```

Program to count the number of words in a file
Developed by: JAYASRI DODDA
Register Number: 212222240028

n=input('Enter File name: ')
wordslen=0
with open(n,'r') as f:
    for line in f:
        words=line.split()
        wordslen+=len(words)
print("Number of wordds:",wordslen)
```

### OUTPUT:
![output](https://github.com/abinayasangeetha/Word-count/assets/119393675/4428cedd-a1bb-411d-ae08-e98310ee61dd)


## RESULT:
Thus the program is written to find the word count from a text.
