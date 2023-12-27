# command-line-arguments-to-count-word
## AIM:
To write a python program for getting the word count from the contents of a file using command line arguments.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Import the sys module.

### Step 2:
Pass the filename as the first argument after the name of script. Open the file as sys.argv[1]

### Step 3:
Read the file using read() method.

### Step 4:
Use split() method to split the file content into words.

### Step 5:
Use len() to find the total words.

### Step 6:
Run the program to determine the number of words in the file created.

## PROGRAM:
```
Developed by : A.Lahari
Registered number : 212223230111
import sys
f=open(sys.argv[1],'r')
a=f.read().split()
word=(len(a))
print("Number of words:",word)
```
### OUTPUT:

![Screenshot 2023-12-27 231716](https://github.com/AnnaLahari/command-line-arguments-to-count-word/assets/149365425/ca5f2cda-19b9-4948-9d54-66d07a5753d3)

![WhatsApp Image 2023-12-27 at 23 20 10_f6fc12b8](https://github.com/AnnaLahari/command-line-arguments-to-count-word/assets/149365425/b57f5861-e9ee-419e-85cb-7415d4c84b22)

## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
