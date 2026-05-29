# Variables and Data Types

## 1. Variables

A variable is a container that stores data.

### Example

```python
name = "Sumit"
age = 20
```

- `name` stores `"Sumit"`
- `age` stores `20`

### Syntax

```python
variable_name = value
```

---

## 2. Data Types

A data type defines what kind of data a variable stores.

| Type | Example |
|--------|--------|
| `str` | `"Sumit"` |
| `int` | `20` |
| `float` | `99.99` |
| `bool` | `True` |
| `list` | `["apple", "banana"]` |
| `tuple` | `(1, 2, 3)` |
| `dict` | `{"name": "Sumit"}` |
| `set` | `{1, 2, 3}` |

### String (`str`)

Stores text.

```python
name = "Sumit"
```

### Integer (`int`)

Stores whole numbers.

```python
age = 20
```

### Float (`float`)

Stores decimal values.

```python
price = 99.99
```

### Boolean (`bool`)

Stores only `True` or `False`.

```python
is_admin = False
```

### Tuple (`tuple`)

- Ordered
- Immutable

```python
numbers = (1, 2, 3)
```

### List (`list`)

- Ordered
- Mutable

```python
fruits = ["apple", "banana", "mango"]
```

### Dictionary (`dict`)

Stores data as key-value pairs.

```python
user = {
    "name": "Sumit",
    "age": 20
}
```

### Set (`set`)

Stores unique values.

```python
numbers = {1, 2, 3, 3, 3}
```

Output:

```python
{1, 2, 3}
```

---

# Practical Examples

## Variable

```python
name = "sumit"
print(name)
```

Output:

```text
sumit
```

---

## Multiple Assignment

```python
name, age = "sumit", 19
```

```python
print(type(name))
print(type(age))
```

Output:

```text
<class 'str'>
<class 'int'>
```

---

## Type Conversion

```python
age = "19"
print(type(age))
```

Output:

```text
<class 'str'>
```

```python
age = int("19")
print(type(age))
```

Output:

```text
<class 'int'>
```

---

## Case Sensitivity

```python
year = 19
Year = "ninety"
```

```python
print(year)
print(Year)
```

Output:

```text
19
ninety
```

Python treats `year` and `Year` as different variables.

---

## List Unpacking

```python
list_data_type = ["one", "two", "three"]
```

```python
A, B, C = list_data_type
```

```python
print(A)
print(B)
print(C)
```

Output:

```text
one
two
three
```

---

## Tuple

```python
tuple_data_type = ("your", "mine")
print(type(tuple_data_type))
```

Output:

```text
<class 'tuple'>
```

---

## Dictionary

```python
dictionary_data_type = {"ctf": 5, "lab": 20}
print(type(dictionary_data_type))
```

Output:

```text
<class 'dict'>
```

---

## Boolean

```python
boolean_data_type = False
print(type(boolean_data_type))
```

Output:

```text
<class 'bool'>
```

---

## Range

```python
range_data_type = range(9)
print(range_data_type)
```

Output:

```text
range(0, 9)
```

```python
print(type(range_data_type))
```

Output:

```text
<class 'range'>
```

---

## Bytes

```python
byte_data_type = b"best"
print(type(byte_data_type))
```

Output:

```text
<class 'bytes'>
```


Note: Notes are based on my learning and hands-on practice. Formatting and organization were assisted by AI.
