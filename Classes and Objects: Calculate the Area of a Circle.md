# Classes and Objects in Python: Calculate the Area of a Circle

## 🎯 Aim
To write a Python program that calculates the **area of a circle** based on the radius provided by the user. This program uses a class named `cse` and a method `mech` to perform the calculation.

## 🧠 Algorithm
1. **Get user input**: Take the radius of the circle as input from the user.
2. **Define the class**: Create a class named `cse`.
3. **Define the method**: Inside the class, define the method `mech` to calculate the area of the circle using the formula:  
   Area = pi *r^2 
4. **Execute the program**: Create an object of the class and call the method with the radius value.

## 🧾 Program
```
import math
class cse:
    def mech(self, r):
        area = math.pi * r * r
        return area
radius = float(input("Enter the radius of the circle: "))
obj = cse()
result = obj.mech(radius)

print("Area of the circle is:", result)
```


## Output
<img width="550" height="260" alt="image" src="https://github.com/user-attachments/assets/7e393f74-7711-42c1-aeec-487e0a0c052e" />



## Result
If the user enters a radius, the program calculates the area using:
