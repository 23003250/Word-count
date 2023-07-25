# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a exsiting text file 
### Step 2: 
 Read the file and store in the variable
### Step 3: 
count=0
### Step 4:  
using for loop split the word 
### Step 5: 
using count+=1
### Step 6: 
print the count
### Step 7:
End the program
## PROGRAM:
```
"""
To write a python program for getting the word count from a text.
Developed by: MIDHUN S 
Reference no: 23003250
"""
with open("myfile.txt","r") as f:
    b=f.read()
    count=0
    for i in b.split():
        count+=1
    print(count)
```

### OUTPUT:
![output](/Screenshot%202023-07-25%20020503.jpg)

i)TEXT FILE
![output](/Screenshot%202023-07-25%20020631.jpg)

## RESULT:
Thus the program is written to find the word count from a text.
