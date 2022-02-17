# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
open text.txt as fp

### Step 2: 
add content to the text.txt file
 
### Step 3: 
use reas mode to read the text.txt

### Step 4:  
split the words in the file using split ()

### Step 5: 
use len(word) to find total number of words

### Step 6: 
print the output

## PROGRAM:
~~~
def program():
    count=0
    with open("text.txt","r") as f:
        for data in f:
            words=data.split()
            for word in words:
                count+=1
    print("Total number of words:",count)
program()
~~~

### OUTPUT:
<img width="752" alt="Screenshot 2022-02-17 at 9 14 54 PM" src="https://user-images.githubusercontent.com/93427522/154519664-e305b208-bc09-4d2d-8b0b-09980ea2059b.png">




## RESULT:
Thus the program is written to find the word count from a text.
