# Copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
start the program
### Step 2: 
open the file 
### Step 3: 
copying the content form the file
### Step 4:  
end the program

## PROGRAM:
```
'''
#Program to copy the file.
#Developed by: VARNIKA.P
#RegisterNumber: 23008344
'''
print("Enter the name of source file: ")
sFile=input()
print("Enter the name of target file: ")
tFile=input()
fileHandle=open(sFile,"r")
texts=fileHandle.readlines()
fileHandle.close()
fileHandle=open(tFile, "w")
for s in texts:
    fileHandle.write(s)
fileHandle.close()
print("\nFile Copied Successfully!")

```
### OUTPUT:

![image](https://github.com/23008344/copy-file/assets/145742655/b97c3bcf-cb6f-4614-ab2a-e7bf69985c37)
![image](https://github.com/23008344/copy-file/assets/145742655/14c6770c-b37e-4afb-9afd-f7578286ebdd)
![image](https://github.com/23008344/copy-file/assets/145742655/205a1ee5-cb47-4cab-bfe8-8b0e082f3e24)


## RESULT:
Thus the program is written to copy the contents from one file to another file.
