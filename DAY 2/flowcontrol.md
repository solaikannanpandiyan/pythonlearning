# Python Flow Controls with Examples

Python provides several flow control statements that help manage the order in which code is executed. These include conditional statements, loops, and loop control statements.

---

## 1. Conditional Statements

### if Statement
```python
x = 10
if x > 5:
    print("x is greater than 5")
```

### if-else Statement
```python
x = 3
if x > 5:
    print("x is greater than 5")
else:
    print("x is less than or equal to 5")
```

### if-elif-else Statement
```python
x = 5
if x > 5:
    print("x is greater than 5")
elif x == 5:
    print("x is equal to 5")
else:
    print("x is less than 5")
```

---

## 2. Loops

### for Loop
```python
for i in range(3):
    print("Iteration", i)
```

### while Loop
```python
count = 0
while count < 3:
    print("Count is", count)
    count += 1
```

---

## 3. Loop Control Statements

### break Statement
```python
for i in range(5):
    if i == 3:
        break
    print(i)
```

### continue Statement
```python
for i in range(5):
    if i == 3:
        continue
    print(i)
```

### pass Statement
```python
for i in range(5):
    if i == 3:
        pass  # Placeholder for future code
    print(i)
```

---

These flow control statements form the backbone of logic in Python programs. Use them to control how your code is executed under various conditions.

