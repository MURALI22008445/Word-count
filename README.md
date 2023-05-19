# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:Decleare number of words is 0

### Step 2:open it with txt file
 
### Step 3:Give range for i

### Step 4:Then nxt split the words  

### Step 5:count the number of words 

### Step 6:Giving print statement for getting output.

## PROGRAM:
```
'''Program to count the words in a file
Developed by: Murali.S
Register Number: 212222230088
'''
fname=input("enter the file name")
num_words=0
with open(fname, 'r') as f:
    for line in f:
        words=line.split()
        num_words+=len(words)
print('Number of words: ',num_words)
```
### OUTPUT:
![murali py](https://github.com/MURALI22008445/Word-count/assets/119643767/c8d4eede-2f26-4a8a-8e75-31a7e82ce3de)

## RESULT:
Thus the program is written to find the word count from a text.
