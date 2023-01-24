# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open a text file as firstfile using with open command
### Step 2: 
 Open another text file as secondfile using with open command
### Step 3: 
Using for loop , reading the content inside firstfile.
### Step 4:  
Copying first file in second file
### Step 5: 
Run the Program. The First file will be copyed in second file
### Step 6: 
End the program
## PROGRAM:
```
#Devolped By: ALDRIN LIJO J E
#Ref no: 22008844
```
```PY
with open('sample.txt','r') as file1:
    with open ('san1.txt','a') as file2:
        for line in file1:
            file2.write(line)
```

### OUTPUT:
![OUTPUT](/op1%20(1).png)
![OUTPUT](/op2.png)


## RESULT:
Thus the program is written to copy the contents from one file to another file.