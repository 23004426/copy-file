# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a text1.txt with some content in it
### Step 2: 
Open the text1.txt file in read mode 
### Step 3: 
Create a copy.txt file using write mode
### Step 4:  
Copy the content of text1.txt file to copy.txt using write function.

## PROGRAM:
```
Program for copying the contents from one file to another file
Developed by: Tirupathi Jayadeep
RegisterNumber: 23004426
with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)
```

### OUTPUT:
![Screenshot 2023-12-25 120603](https://github.com/23004426/copy-file/assets/144979327/2830b9ab-a02c-4864-93ef-3910626e005d)

![Screenshot 2023-12-25 120621](https://github.com/23004426/copy-file/assets/144979327/9c6a6229-b32f-4737-97b0-6c4e406c66a5)

![Screenshot 2023-12-25 120635](https://github.com/23004426/copy-file/assets/144979327/99b5e0fb-be7d-41ac-a500-743e17a25502)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
