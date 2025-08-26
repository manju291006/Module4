# Exp. No: 4a  
## Dictionary–  convert them into a dictionary in a way that item from list1 is the key and item from list2 is the value. Get two lists as input.
###  Aim
To Write a Python program to convert them into a dictionary in a way that item from list1 is the key and item from list2 is the value. Get two lists as input.
###  Algorithm

Step 1: Start the program.
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions.
Step 4: Display the result/output to the user.
Step 5: Stop the program.


### 🧾 Program
```

keys=input()
values=input()
keys=eval(keys)
values=eval(values)
result=dict(zip(keys,values))
print(result)

```


### OUTPUT

<img width="770" height="233" alt="image" src="https://github.com/user-attachments/assets/abc41254-ab32-41fc-8d8d-bcb94965c1a9" />


### Result 

Thus the program was executed successfully 





# Exp. No: 4b 
## Exception – the solution of value error in exception handling and check whether the number is even or odd.

###  Aim
To write a python program for the solution of value error in exception handling and check whether the number is even or odd. 
###  Algorithm

Step 1: Start the program.
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions.
Step 4: Display the result/output to the user.
Step 5: Stop the program.


### 🧾 Program
```
try:
    x=input()
    b=int(x)
    if b%2==0:
        print("You entered even number")
    else:
        print("An odd number")
except ValueError:
    print("Enter only number")

```


### OUTPUT

<img width="636" height="257" alt="image" src="https://github.com/user-attachments/assets/7cfe7c3d-5729-48a3-9bfa-0923e42f9539" />


### Result 

Thus the program was executed successfully 






# Exp. No: 4c 
## Files Modules – Write a Python program to read a file and count the frequency of each character in it.

###  Aim
To Write a Python program to read a file and count the frequency of each character in it.
### Algorithm
Step 1: Start the program.
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions.
Step 4: Display the result/output to the user.
Step 5: Stop the program.


### 🧾 Program
```
from collections import defaultdict
def create_file(file_path,content):
    with open(file_path, 'w') as file:
        file.write(content)
def char_frequency(file_path):
    freq_dict=defaultdict(int)
    with open(file_path,'r') as file:
        content=file.read()
        for char in content:
            freq_dict[char]+=1
    return freq_dict
```


### OUTPUT

<img width="781" height="308" alt="image" src="https://github.com/user-attachments/assets/bbc7d90f-99b1-4bfb-a123-4fe93edf1cc9" />


### Result 

Thus the program was executed successfully 






# Exp. No: 4d  
## Classes & Objects – Write Python Program to take the radius from the user and find the area of the circle using class name 'pen' and function name 'stationary'

###  Aim
To Write Python Program to take the radius from the user and find the area of the circle using class name 'pen' and function name 'stationary'
###  Algorithm

Step 1: Start the program.
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions.
Step 4: Display the result/output to the user.
Step 5: Stop the program.


### 🧾 Program
```
import math

class cse:
    def mech(self, radius):
        area = math.pi * radius * radius
        print(f"Area of circle: {area:.2f}")

# Take input from user
r = float(input())

# Create object and call method
obj = cse()
obj.mech(r)

```


### OUTPUT
<img width="628" height="175" alt="image" src="https://github.com/user-attachments/assets/b61749f6-2465-46d6-aea3-df67d4241daa" />



### Result 

Thus the program was executed successfully 






# Exp. No: 4e  
## SEB – Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError.

###  Aim
To Place result="You can't divide with 0" to the right place so that program avoids ZeroDivisionError.
###  Algorithm

Step 1: Start the program.
Step 2: Take the necessary input(s) from the user.
Step 3: Process the input(s) using suitable operations or conditions.
Step 4: Display the result/output to the user.
Step 5: Stop the program.


### 🧾 Program
```
a=int(input())
b=int(input())
try:
    result=a/b
    print(result)
except ZeroDivisionError:
    print("You can't divide with 0")
     




```


### OUTPUT

<img width="637" height="308" alt="image" src="https://github.com/user-attachments/assets/37478017-6719-4e61-afe6-7272de18865c" />


### Result 

Thus the program was executed successfully 

