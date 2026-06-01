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
def merge(dict1, dict2):
    return {**dict1, **dict2}

dict1 = {'a': 1, 'b': 2, 'c': 3}
dict2 = {'b': 4, 'd': 5}

merged_dict = merge(dict1, dict2)
print("Merged dictionary:", merged_dict)
```

## Output
<img width="1163" height="941" alt="image" src="https://github.com/user-attachments/assets/7a0ba945-5455-4ac2-82ba-55580ff7c4ec" />

## Result
Thus To write a Python program that merges two dictionaries and combines their key-value pairs has been executed sucessfully.
