# Copy-File
## AIM:
To write a python program for copying the contents from one file to another file.
## EQUIPEMENT'S REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM:
```
Step 1:
Load the CSV into a DataFrame.

Step 2:
Print the number of contents to be displayed using df.head().

Step 3:
The number of rows returned is defined in Pandas option settings.

Step 4:
Check your system's maximum column with the pd.options.display.max_column statement.

Step 5:
Increase the maximum number of rows to display the entire DataFrame

Step 6:
End the program.
```

## PROGRAM:
```
#To write a python program for reading content from a CSV file.
#Developed by: MURALI KRISHNA S
#Register Number: 212223230129

def copy(fname,newfile):
  with open(fname) as fp:
    with open(newfile,'w') as fp1:
      data=fp.read()
      fp1.write(data)
copy("file1.txt","python.txt")      

```


#OUTPUT:
![image](https://github.com/Murali-Krishna0/Copy-File/assets/149054535/6d43a57a-8b24-465b-907b-701dd2c86ec9)
![image](https://github.com/Murali-Krishna0/Copy-File/assets/149054535/2b335f18-0aaa-4cc6-b288-0495ab988c9e)
![image](https://github.com/Murali-Krishna0/Copy-File/assets/149054535/92f1436b-2b79-47a2-bd9d-8aad9b2d1697)






## RESULT:
Thus the program is written to copy the contents from one file to another file.
