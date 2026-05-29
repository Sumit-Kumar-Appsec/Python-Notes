# VARIABLES AND DATA TYPES

#### 1. Variable = A variable is a container that stores data

```python
name = "Sumit"
age = 20
```

> name stores "Sumit", age stores 20

#### Syntax = variable_name=value

#### 2. Data Types = A data type tells what kind of data a variable stores.

1. String (`str`) = Stores text or words. Ex - { name = "Sumit", city = "Patna" }

2. Integer (`int`) = Stores whole numbers. Ex - { age = 20, marks = 95 }

3. Float (`float`) = Stores decimal numbers. Ex - { price = 99.99, pi = 3.14 }

4. Boolean (`bool`) = Stores only `True` or `False`. Ex - { is_admin = True, is_logged_in = False }

5. Tuple (`tuple`) = Stores multiple values in a fixed collection.
   - Ordered
   - Cannot be changed after creation
   - Ex = numbers = (1, 2, 3)

6. List (`list`) = Stores multiple values in one variable.
   - Ordered
   - Can be changed
   - Ex = fruits = ["apple", "banana", "mango"]

7. Dictionary (`dict`) = Stores data in key-value pairs.

```python
user = {
    "name": "Sumit",
    "age": 20
}
```

8. Set (`set`) = Stores unique values only.
   - Duplicate values are automatically removed.
   - Ex = numbers = {1, 2, 3, 3, 3}
   - Output = {1, 2, 3}

---

### Code Snippet

```python
name = "sumit"             # variable

print(name)
```

Output:

```text
sumit
```

```python
name, age = "sumit", 19    # multiple assignment

print(type(name))
print(type(age))
```

Output:

```text
<class 'str'>
<class 'int'>
```

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

```python
year = 19                  # 'y' case sensitive variable
Year = "ninety"            # 'Y' case sensitive variable

print(year)
print(Year)
```

Output:

```text
19
ninety
```

> two different variables

```python
list_data_type = ["one", "two", "three"]      # square brackets []

print(list_data_type)

A, B, C = list_data_type                      # unpack

print(A)
print(B)
print(C)

print(list_data_type)
```

Output:

```text
['one', 'two', 'three']

one
two
three

['one', 'two', 'three']
```

```python
tuple_data_type = ("your", "mine")            # parentheses ()

print(type(tuple_data_type))
```

Output:

```text
<class 'tuple'>
```

```python
dictionary_data_type = {"ctf": 5, "lab": 20}  # curly braces {}

print(type(dictionary_data_type))
```

Output:

```text
<class 'dict'>
```

```python
boolean_data_type = False                     # True / False

print(type(boolean_data_type))
```

Output:

```text
<class 'bool'>
```

```python
range_data_type = range(9)

print(range_data_type)

print(type(range_data_type))
```

Output:

```text
range(0, 9)
<class 'range'>
```

```python
byte_data_type = b"best"

print(type(byte_data_type))
```

Output:

```text
<class 'bytes'>
```

---

**Disclaimer:** Content learned and tested by me. Formatting assistance from AI.
