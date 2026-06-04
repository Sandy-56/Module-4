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
def sort_dict_by_values(d):
    return sorted(d.items(), key=lambda item: item[1])
my_dict = {3: 323,2: 56,4: 24, 6: 18,5: 12, 1: 2}
sorted_items = sort_dict_by_values(my_dict)
print("Keys and Values sorted in alphabetical order by the value")
print(sorted_items)
```

## Sample Output
<img width="1176" height="299" alt="image" src="https://github.com/user-attachments/assets/47a93cef-654d-492f-bd53-20739406486c" />

## Result

Thus the Python program to sort a dictionary is executed successfully.
