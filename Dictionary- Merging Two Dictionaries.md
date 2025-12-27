## Dictionary Operations in Python: Merging Two Dictionaries

## 🎯 Aim
To write a Python program that merges **two dictionaries** and combines their key-value pairs.

## 🧠 Algorithm
1. Define two dictionaries `dict1` and `dict2` with some key-value pairs.
2. Define a function `merge()` that merges the two dictionaries using the `**` unpacking operator.
   - The merged result will combine keys from both dictionaries. If a key exists in both, the value from `dict2` will overwrite that from `dict1`.
3. Call the `merge()` function and print the merged dictionary.

## 🧾 Program
```
dict1={"car":"volvo","model":"TN1","year":2025}
dict2={"car":"washa","model":"TN2","year":2026}
def merge(dict1,dict2):
       merged={**dict1,**dict2}
       return merged
print(merge(dict1,dict2))
     
```

## Output
<img width="918" height="778" alt="image" src="https://github.com/user-attachments/assets/8c637c2f-872f-4717-b389-645a54e8ba9b" />


## Result
The program was run and executed successfully.
