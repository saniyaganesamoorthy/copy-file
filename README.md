# copy-file
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
# Step 1:
Create a text1.txt with some content in it

# Step 2:
Open the text1.txt file in read mode

# Step 3:
Create a copy.txt file using write mode

# Step 4:
Copy the content of text1.txt file to copy.txt using write function

# Step 5:
End the program

## PROGRAM:
```
'''
Devolped by: SANIYA G
Register number: 212223240147
'''
def fun(filename,newfilename):
    with open(filename) as fp:
        with open(newfilename,'w') as fp1:
            data=fp.read()
            fp1.write(data)
filename=input("Enter the file to read the content: ")
newfilename=input("Enter the file to store copied content: ")
fun(filename,newfilename)
```


### OUTPUT:
![Alt text](<Screenshot 2024-01-02 082148.png>)
![Alt text](<Screenshot 2024-01-02 082355.png>)
![Alt text](<Screenshot 2024-01-02 091948.png>)


## RESULT:
Thus the program is written to copy the contents from one file to another file.