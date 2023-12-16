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
file= open(sys.argv[1])
data=file.read()
words=data.split()
print("Total Words:",len(words))

```
### OUTPUT:

![image](https://github.com/AnnaLahari/command-line-arguments-to-count-word/assets/149365425/a25ea266-b527-4dae-a6ea-7bc59750834c)

![WhatsApp Image 2023-12-16 at 10 23 41_f4e1ac57](https://github.com/AnnaLahari/command-line-arguments-to-count-word/assets/149365425/81a3764c-5b05-4b37-957f-4bac3a3454ea)


## RESULT:
Thus the program is written to find the word count from the contents of a file using command line arguments.
