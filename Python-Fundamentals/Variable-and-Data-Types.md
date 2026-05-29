#### 1. Variable = A variable is a container that stores data            
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
