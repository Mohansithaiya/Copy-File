# DATE:
# EX.NO.11 Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Define the function as copy with arguements as existing file name and new file name.
### Step 2: 
Open the existing file to read. 
### Step 3: 
Open the new file to write.
### Step 4:  
Copy the contents from existing file to new file.
### Step 5: 
Get the inputs from the user for existing file and new file. Call the function.
### Step 6: 
End the program.
## PROGRAM:
```python
Program for copying the contents from one file to another file
Developed by: MOHAN S
RegisterNumber: 212223240094

with open("text1.txt",'r') as fp:
    msg1=fp.read()
with open("copytxt",'w') as fp1:
    fp1.write(msg1)

```
### OUTPUT:
![Screenshot 2024-10-16 134250](https://github.com/user-attachments/assets/c4dfa5b0-d438-4c7a-a0be-3de25f07e489)
![Screenshot 2024-10-16 134302](https://github.com/user-attachments/assets/bbb6dffc-3c1c-4bff-a2da-151d82c985a3)
![Screenshot 2024-10-16 134312](https://github.com/user-attachments/assets/1c3d5d53-99c1-4e3e-a9ef-bf833aef00f1)

## RESULT:
Thus the program is written to copy the contents from one file to another file.
