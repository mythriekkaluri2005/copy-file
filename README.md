# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Create a file.
### Step 2: 
Write some lines in that file. 
### Step 3: 
Create a python file.
### Step 4:  
Write a code to copy the content of the file to a new file.
### Step 5: 
Run the program.
### Step 6: 
Display the output.
## PROGRAM:
Developed by:Ekkaluri Mythri
RegisterNumber: 23003922

def copy(filename,newfile):
    with open(filename,'r') as fp:
        with open(newfile,'w') as fp1:
            data1=fp.read()
            fp1.write(data1)
filename=input("Enter an Existing File:")
newfile=input("Enter a name for new file:")
copy(filename,newfile)

### OUTPUT:
![Screenshot 2023-12-29 105336](https://github.com/mythriekkaluri2005/copy-file/assets/150231422/ee84d4d2-9a06-45ab-bc25-57e347131fc1)
![Screenshot 2023-12-29 105353](https://github.com/mythriekkaluri2005/copy-file/assets/150231422/6cfb0016-5fd0-43ec-8124-fad1874ebef2)



## RESULT:
Thus the program is written to copy the contents from one file to another file.
