# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
## Step 1:
Create a file and add some content into it.

## Step 2:
Open file using with keyword/built-in function in read mode.

## Step 3:
Use read() to read the contents of the file.

## Step 4:
Split the lines using split().

## Step 5:
Iterate the list and increment the count

## Step 6:
Print the output.

## PROGRAM:
```
To write a program for getting the word count from a file.
Developed by: K.M.Swetha
RegisterNumber: 21500844

def wordcount():
    cnt = 0
    with open("MyFile.txt","r") as fp:
        data = fp.read()
        for line in data.split():
            cnt += 1
    print("The number of words in the given file is:",cnt)
wordcount()
```

### OUTPUT:
![image](https://user-images.githubusercontent.com/94228215/154516857-197d56fe-6e8a-4047-9a4f-4e79542a1b82.png)
![image](https://user-images.githubusercontent.com/94228215/154516926-1217e520-0390-45ce-9f97-86f3d0a9c851.png)




## RESULT:
Thus the program is written to find the word count from a text.
