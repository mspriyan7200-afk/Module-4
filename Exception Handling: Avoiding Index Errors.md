<img width="1727" height="361" alt="image" src="https://github.com/user-attachments/assets/ba9fa293-6700-4118-871e-815e22add160" /># Exception Handling in Python: Avoiding Index Errors

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
list1 = [10, 20, 30]

try:
    print(list1[5])
except IndexError:
    print("You're out of list range")
```

## Output
<img width="957" height="246" alt="530542844-cd368d76-0e42-44fb-9b9f-9745a8539df0" src="https://github.com/user-attachments/assets/f0efffed-0b9b-41a6-8585-ee87cf1a91d0" />


## Result
