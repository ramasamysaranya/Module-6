# 🐟 Method Overriding-Fish and Shark Class Inheritance in Python

## 🧠 AIM:
To write a Python program that demonstrates class inheritance by creating a parent class `Fish` with a method `type`, and a child class `Shark` that overrides the `type` method.

## 📋 ALGORITHM:

1. Define the `Fish` class with a method named `type()` that prints `"fish"`.
2. Define the `Shark` class as a subclass of `Fish`, and override the `type()` method to print `"shark"`.
3. Create an instance of the `Fish` class named `obj_goldfish`.
4. Create an instance of the `Shark` class named `obj_hammerhead`.
5. Use a `for` loop to iterate over both objects.
6. Within the loop, call the `type()` method using the loop variable.
7. Output will demonstrate method overriding: printing `"fish"` and `"shark"` accordingly.

## 💻 PROGRAM:
~~~
class Fish:
    def water(self):
        print("fish")
       

class Shark:
    def water(self):
        print("shark")
	

obj_goldfish=Fish()
obj_hammerhead=Shark()

obj_goldfish.water()
obj_hammerhead.water()
~~~
## OUTPUT
<img width="1920" height="1020" alt="image" src="https://github.com/user-attachments/assets/313a16f6-ba80-4232-9af4-3b771828a966" />

## RESULT
Thus, the program has been executed successfully.
