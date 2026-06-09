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
d = {'c': 'cat', 'a': 'apple', 'b': 'ball'}

print("Original Dictionary:", d)

sorted_keys = dict(sorted(d.items()))
print("Sorted by Keys:", sorted_keys)

sorted_values = dict(sorted(d.items(), key=lambda item: item[1]))
print("Sorted by Values:", sorted_values)
```
## Sample Output
```
Original Dictionary: {'c': 'cat', 'a': 'apple', 'b': 'ball'}
Sorted by Keys: {'a': 'apple', 'b': 'ball', 'c': 'cat'}
Sorted by Values: {'a': 'apple', 'b': 'ball', 'c': 'cat'}
```
## Result
```
The program was executed successfully and displayed the dictionary sorted by keys and by values.
```
