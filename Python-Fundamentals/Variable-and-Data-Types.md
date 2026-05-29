
    - VARIABLES AND DATA TYPES
        
        #### 1. Variable = A variable is a container that stores data
        
        ```
        name = "Sumit"
        age = 20
        ```
        
        > name stores "Sumit"  , age stores 20
        > 
        
        #### Syntax = variable_name=value
        
        #### **2.Data Types = A data type tells what kind of data a variable stores.**
        
        1. String (`str`) = Stores text or words. Ex - { name = "Sumit” , city = "Patna” }
        2. Integer (`int`) = Stores whole numbers. Ex -  { age = 20 , marks = 95 }
        3. Float (`float`) = Stores decimal numbers. Ex - { price = 99.99 , pi = 3.14 }
        4. Boolean (`bool`) = Stores only `True` or `False`. Ex - { is_admin = True , is_logged_in = False }
        5. Tuple (`tuple`) = Stores multiple values in a fixed collection.
            - Ordered
            - Cannot be changed after creation
            - Ex = numbers = (1, 2, 3)
        6. List (`list`) = Stores multiple values in one variable.
            - Ordered
            - Can be changed
            - Ex = fruits = ["apple", "banana", "mango"]
        7. Dictionary (`dict`) = Stores data in key-value pairs.
            
            ```jsx
            user = {
                "name": "Sumit",
                "age": 20
            }
            ```
            
        8. Set (`set`) = Stores unique values only.
            - Duplicate values are automatically removed.
            - Ex = numbers = {1, 2, 3, 3, 3} , Output : {1, 2, 3}
        - code snippet
            
            ```python
            name = "sumit".            -- varialabe
            print(name)
            sumit
            ```
            
            ```python
            name, age = "sumit", 19.   -- multiple assginment
            
            print(type(name))          -- identify variable types
            <class 'str'>
            
            print(type(age))           -- identify variable types
            <class 'int'>
            ```
            
            ```python
            age = "19"
            print(type(age))          -- string
            <class 'str'>            
            
            age = int("19")
            print(type(age))          -- integer
            <class 'int'>
            ```
            
            ```python
            year = 19                  -- 'y' case sensetive variable
            Year = "ninety"            -- 'Y' case sensetive variable
            
            print(year); print(Year)
            19
            ninety             -- two diffrent vairables
            ```
            
            ```python
            list_data_type = ["one", "two", "three"]      -- SQUARE BRACKER []
            print(list_data_type)
            ['one', 'two', 'three']
            
            A, B, C = list_data_type                      -- unpack
            
            print(A); print(B); print(C)
            one
            two
            three
            
            print(list_data_type)
            ['one', 'two', 'three']
            ```
            
            ```python
            tuple_data_type = ("your", "mine").       -- PARENTHESES BRACKER ()
            print(type(tuple_data_type))
            <class 'tuple'>
            ```
            
            ```python
            dictionary_data_type = {"ctf": 5, "lab": 20}
            print(type(dictionary_data_type))            -- CURLY BRACKER {}
            <class 'dict'>                             -- WITH VALUES,EX- 5,20
            ```
            
            ```python
            boolean_data_type = False         -- two type only = True, False
            print(type(boolean_data_type))
            <class 'bool'>
            ```
            
            ```python
            range_data_type = range(9)        -- range(range-number)
            
            print(range_data_type)
            range(0, 9)
            
            print(type(range_data_type))
            <class 'range'>
            ```
            
            ```python
            byte_data_type = b"best"         
            print(type(byte_data_type))
            <class 'bytes'>
            
            ```
