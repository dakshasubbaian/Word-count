# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPMENTS REQUIRED: 
PC
Anaconda - Python 3.7
## ALGORITHM: 
### Step 1:
Open the file as a read mode

### Step 2: 
Assign a variable to store the data
 
### Step 3: 
Using f.read().split() and storing that in assgined variable as x

### Step 4:  
y=len(x)

### Step 5: 
Print the number of words y

### Step 6: 
End the program

## PROGRAM:
```
#To find no.of words in the csv file
#Developed by : Daksha Subbaian
#Register number : 212223230036

from google.colab import drive
drive.mount('/content/drive')

with open("/content/drive/MyDrive/python.txt",'r') as f:
  x=f.read().split()
  y=len(x)
print("Number of words :",y)
```

### OUTPUT:
![image](https://github.com/user-attachments/assets/0d1c278b-8c44-418e-ac19-4a8a7e4e0dad)
![output](/5a\)txt.png)



## RESULT:
Thus the program is written to find the word count from a text.
