# Exception Handling in Python: Avoiding Index Errors

## 🎯 Aim
To write a Python program that handles an **IndexError** when trying to access an element beyond the available range of a list.

## 🧠 Algorithm
1. Define a list `list1` with some integer elements.
2. Use a **try-except** block:
   - In the `try` block, attempt to access an index that is out of range (e.g., `list1[5]`).
   - In the `except` block, catch the error and print a custom message `"You're out of list range"`.
3. Print the result based on whether the index access succeeds or fails.

## 🧾 Program
```
list1 = [10, 20, 30, 40]

try:
    # Attempt to access an out-of-range index
    value = list1[5]
    print("Accessed value:", value)
except IndexError:
    print("You're out of list range")
```

## Output
<img width="1051" height="812" alt="image" src="https://github.com/user-attachments/assets/1e3846fc-cd89-4a55-92f5-f569e3bcb345" />

## Result
Thus To write a Python program that handles an IndexError when trying to access an element beyond the available range of a list hass been executed sucessfully.
