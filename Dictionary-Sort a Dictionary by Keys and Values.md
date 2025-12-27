# 🔤 Dictionary-Python Program to Sort a Dictionary by Keys and Values

This Python program demonstrates how to sort a dictionary:
- Alphabetically by keys
- Alphabetically by values

---

## 🎯 Aim

To write a Python program that sorts a dictionary's:
- Keys in alphabetical order
- Values in alphabetical order

---

## 🧠 Algorithm

1. **Start the program.**
2. **Define** a dictionary with key-value pairs.
3. **Sort by Keys**:
   - Use `sorted(dictionary.items())`
   - Convert the result to a dictionary using `dict()`
4. **Sort by Values**:
   - Use `sorted(dictionary.items(), key=lambda item: item[1])`
   - Convert the result to a dictionary using `dict()`
5. **Display** the original and sorted dictionaries.
6. **End the program.**

---

## 🧪Program
```
dictonary=eval(input())
sortkeys=dict(sorted(dictonary.items()))
sortvalues=dict(sorted(dictonary.item(),key=lambda item:item[1]))
print(dictonary)
print(sortkeys)
print(sortvalues)
```

## Sample Output
<img width="918" height="778" alt="image" src="https://github.com/user-attachments/assets/2e35f658-b0b1-4bcb-afb0-71cf11228306" />

## Result
The program was run and executed successfully.
