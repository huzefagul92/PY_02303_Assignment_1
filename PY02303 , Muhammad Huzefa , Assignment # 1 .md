```python
# Q1 of Assignment # 1
# Write a Python program to print the following string in a specific format
# ---------------------------------------

print("Twinkle, twinkle, Little star,")
print("       How I wonder what you are!")
print("              Up above the world so high,")
print("              Like a diamond in the sky.")
print("Twinkel, Twinkle, Little star,")
print("       How I wonder what you are!")

```

    Twinkle, twinkle, Little star,
           How I wonder what you are!
                  Up above the world so high,
                  Like a diamond in the sky.
    Twinkel, Twinkle, Little star,
           How I wonder what you are!
    


```python
# Q2 of Assignment # 1
# Write a Python program to get the Python version you are using
# ---------------------------------------

# sys is the module
import sys 

print("the current Python version in my system is :")

# .version is function
print ("    "+sys.version) 


print("Version info:")

# .version_info is the function
print (sys.version_info) 
```

    the current Python version in my system is :
        3.7.4 (default, Aug  9 2019, 18:34:13) [MSC v.1915 64 bit (AMD64)]
    Version info:
    sys.version_info(major=3, minor=7, micro=4, releaselevel='final', serial=0)
    


```python
# Q3 of Assignment # 1
# Write a Python program to display the current date and time.
# ---------------------------------------

# datetime is a module
import datetime

#datetime.datetime the second one is an attributes while now is the function
now = datetime.datetime.now()

print("Current date and time : ")

# strftime is a function.
print(now.strftime('%Y-%m-%d %H:%M:%S')) 

# %h %m etc are directives which has special meaning.
print(now.strftime('%H:%M:%S on %A, %B the %dth, %Y')) 


```

    Current date and time : 
    2019-11-02 20:25:24
    20:25:24 on Saturday, November the 02th, 2019
    


```python
# Q4 of Assignment # 1
# Write a Python program which accepts the radius of a circle from the user and compute the area.
# ---------------------------------------

# importing pi module from math.py
from math import pi

#taking radius as user input
radius = float(input("please enter the radius value : "))
print("you entered",radius,"as a radius")

area = float(pi*radius**2)
print("the area is :", area)


```

    please enter the radius value : 1000
    you entered 1000.0 as a radius
    the area is : 3141592.653589793
    


```python
# Q5 of Assignment # 1
# Write a Python program which accepts the user's first and last name and 
# print them in reverse order with a space between them.
# ---------------------------------------

first_name = str(input("Enter your good First Name, Please!\n   "))
last_name = str(input("Enter your good Last Name, Please!\n   "))

print("\n" + last_name + "  " + first_name)


```

    Enter your good First Name, Please!
       muhammad usama
    Enter your good Last Name, Please!
       gul
    
    gul  muhammad usama
    


```python
# Q6 of Assignment # 1
# Write a python program which takes two inputs from user and 
# print them addition
# ---------------------------------------

input_1 = float(input("Enter your first desire number input\n   "))
input_2 = float(input("Enter your second desire number input\n   "))

summation = input_1 + input_2
print("the addition of two number inputs is : ", summation)


```
