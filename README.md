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

fp=input("Enter the file name:")
words=0
with open(fp,'r') as f:
  for line in f:
    word=line.split()
    words+=len(word)
print("Number of words:",words)
```

### OUTPUT:
![PYTHON 5a](https://github.com/Nandhinijaya/Word-count/assets/121998147/b4a4074d-9275-4e72-92d5-60624d3fb30a)

![5a out](https://github.com/Nandhinijaya/Word-count/assets/121998147/a9892cb2-5e5e-4f2c-b107-8a51f1afb61b)


## RESULT:
Thus the program is written to find the word count from a text.
