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
from math import pi
radius=int(input("Enter the radius of the circle: "))
class cse:
   r=radius
   def mech(self):
      Area = pi*self.r**2
      return Area
obj=cse()
print(obj.mech())

```
## Output
<img width="916" height="778" alt="image" src="https://github.com/user-attachments/assets/4e268545-b0d8-4acc-9bd3-ee00388cba67" />

## Result
The program was run and executed successfully.
