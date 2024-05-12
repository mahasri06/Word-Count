# Word-Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:

## Step 1:
Import numpy as np

## Step 2:
Enter the input values

## Step 3:
Write python program for getting the word count from the contents of a file using command line arguments

## Step 4:
Run the program

## Step 5:
Input the values

## Step 6:
End the program

## PROGRAM:
```
#program to find the number of words in a text file
#Developed By:Mahasri P
#Register Number : 212223100029
num=0

with open("untitled.txt","r") as f1:

    for i in f1:

        word=i.split()

        num += len(word)

print("The number of words are in the file is ",num)
```
##OUTPUT:
![WhatsApp Image 2024-05-12 at 03 24 12_de4e6de1](https://github.com/mahasri06/Word-Count/assets/139841897/3275f2bb-3bc3-47a0-84e2-ddaf18180cd2)


## RESULT:
Thus the program is written to find the word count from a text.
