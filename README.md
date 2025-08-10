📚 Week Two Python List Assignment

📝 Description

This project demonstrates fundamental **Python list operations** as part of a Week Two programming assignment.
It covers how to **create, insert, extend, remove, sort**, and **search** within a list.


## 🔹 Steps Performed

1. **Create** an empty list named `my_list`.
2. **Append** elements: `10, 20, 30, 40`.
3. **Insert** `15` at the second position (index `1`).
4. **Extend** the list with `[50, 60, 70]`.
5. **Remove** the last element from the list.
6. **Sort** the list in ascending order.
7. **Find** and print the index of the value `30`.

## 💻 Code Implementation

```python
Week Two Assignment - List Operations

my_list = []                              # Create empty list
my_list.extend([10, 20, 30, 40])          # Append elements
my_list.insert(1, 15)                     # Insert 15 at index 1
my_list.extend([50, 60, 70])               # Extend with new list
my_list.pop()                              # Remove last element
my_list.sort()                             # Sort ascending
print("Final list:", my_list)              # Print final list
print("Index of value 30:", my_list.index(30))  # Print index of 30
```

## 📌 Expected Output

```
Final list: [10, 15, 20, 30, 40, 50, 60]
Index of value 30: 3
```

## 📂 Repository Structure

```
week_two_assignment/
│-- list_assignment.py   # Main Python script
│-- README.md            # Project documentation
```


## 🚀 How to Run

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/week_two_assignment.git
   ```
2. Navigate into the folder:

   ```bash
   cd week_two_assignment
   ```
3. Run the Python file:

   ```bash
   python list_assignment.py
   ```
