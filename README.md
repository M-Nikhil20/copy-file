# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1: 
use open function to open the file in which we want to copy from and access it in read mode

### Step 2: 
read the file and store in a variable
 
### Step 3: 
now create a new file in which we want to paste the content using write access mode

### Step 4:  
use write function to copy the read file that has been stored in variable

### Step 5: 
the content in orginal file will be copied in new file

### Step 6: 
end the program

## PROGRAM:
Devloped by : M Nikhil

Register number : 22008584
```
with open("sample1.txt","r")as firstfile:
    with open("sample2.txt","a")as second file:
        for line firstfile:
            secondfile.write(line)
```            

### OUTPUT:
### SAMPLE1.TXT:
![OUTPUT](/sample%20txt%201.png)

### SAMPLE2.TXT:
![OUTPUT](/sample%20txt%202.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.