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
dict1 = {
    "a": 10,
    "b": 20,
    "c": 30
}

dict2 = {
    "b": 200,
    "d": 40,
    "e": 50
}

def merge(d1, d2):
    merged_dict = {**d1, **d2}
    return merged_dict


result = merge(dict1, dict2)

print("Merged Dictionary:", result)
```


## Output
<img width="757" height="229" alt="image" src="https://github.com/user-attachments/assets/44fe8f75-737e-4d16-802d-ca2d7ba7f571" />


## Result
The Python program successfully merges two dictionaries using the unpacking (**) operator. All key-value pairs from both dictionaries are combined into a single dictionary. If a key is present in both dictionaries, the value from the second dictionary overwrites the value from the first.

The final merged dictionary contains all unique keys with their corresponding values.
