# 🐍 Day 2: Variables and Data Types

## 📖 Theory

### What is a Variable?

A variable is a named container used to store data in memory. The value stored in a variable can be changed during program execution.

**Example:**

```python
name = "Gobind"
age = 23
```

Here:
- `name` is a variable that stores a string.
- `age` is a variable that stores an integer.

---

### What are Data Types?

A data type defines the type of value stored in a variable.

| Data Type | Example |
|-----------|---------|
| Integer (`int`) | `23` |
| Float (`float`) | `5.2` |
| String (`str`) | `"Gobind"` |
| Boolean (`bool`) | `True` |

---

### Program

```python
age = 23
height = 5.2
name = "Gobind"
is_student = True

print(type(age))
print(type(height))
print(type(name))
print(type(is_student))
```

### Output

```text
<class 'int'>
<class 'float'>
<class 'str'>
<class 'bool'>
```

### Key Points

- Variables store data.
- Python automatically detects the data type.
- Use `type()` to check the data type of a variable.
