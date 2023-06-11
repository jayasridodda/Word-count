# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open then required file by using the function"with"
### Step 2: 
  Using split function to split the words.
### Step 3: 
Finding the length of the words by using len() function.
### Step 4:  
Calling the function and printing the number of words.

## PROGRAM:
```
#Developed By: JAYASRI DODDA
#Register No: 212222240028

num_word=0
with open("My File.txt","r")as file1:
    for i in file1:
        word=i.split()
        num_word+=len(word)
print("number of words {}".format(num_word))
```
### OUTPUT:
![Screenshot (66)](https://github.com/jayasridodda/Word-count/assets/123259278/8359657a-a30f-48e5-9ca4-32ebab30b643)



## RESULT:
Thus the program is written to find the word count from a text.
