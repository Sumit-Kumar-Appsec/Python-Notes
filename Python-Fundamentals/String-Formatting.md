- # STRING FORMATTING
    
    ```python
    string_1 = "hello"         -- USING DOUBLE QUOTE
    string_2 = 'byyyyyy'       -- USING SINGLE QUOTE
    
    In [3]: print(type(string_1)); print(type(string_2))
    <class 'str'>
    <class 'str'>
    
    print(string_1); print(string_2)
    hello
    byyyyyy
    ```
    
    ```python
    string_3 = """i am longest          --MULTILINE STRING 
       ...: string_0
       ...: 
       ...: hereeeeeee"""
       
    print(string_3)
    i am longest
    string_0
    
    hereeeeeee
    ```
    
    ```python
    quote = "I\"am a double quote within the double quote"        -- \"
    
    print (quote)
    I"am a double quote within the double quote
    ```
    
    ```python
    quote_2 = 'I\'am a single quote within tha single quote'     --\'
    
    print(quote_2)
    I'am a single quote within tha single quote
    ```
    
    ```python
    newline = "I\"am string\nI\"am a new line"      -- new line = \n
    
    print(newline)
    I"am string
    I"am a new line
    ```
    
    ```python
    escape_backslash = "\\ \x41\x42\x43"     -- use double slash will print slash \\ = \
    
    print(escape_backslash)
    \ ABC
    ```
    
    ```python
    string_7 = "ababababababab"         
    
    print(string_7)             
    ababababababab
    
    string_7 = "ab" * 7                -- multiply strings
    
    print(string_7)
    ababababababab
    
    print(len(string_7))              -- built-in lenth function
    14
    ```
    
    ```python
    newline = "I\"am string\nI\"am a new line" 
    
    print("new" in newline)        --find certain item stored in with strings
    True
    
    print("hello" in newline)
    False
    ```
    
    ```python
    newline = "I\"am string\nI\"am a new line" 
    
    print(quote_2.startswith("i"))      -- (stringname.startswith("keyword"))
    False
    
    print(quote_2.startswith("I"))
    True
    ```
    
    ```python
    quote_2 = 'I\'am a single quote within tha single quote'
    
    print(quote_2.index("within"))         -- find index
    20
    ```
    
    ```python
    print(quote_2.upper())      -- modify the string into uppercase
    I'AM A SINGLE QUOTE WITHIN THA SINGLE QUOTE
    
    print(quote_2.lower()).      -- modify the string into lowercase
    i'am a single quote within tha single quote
    ```
    
    ```python
    messy_data = '    yeeaah haalo!  '
    
    print(messy_data)                -- print all spaces too
        yeeaah haalo!  
    
    print(messy_data.strip())        -- remove spaces and print clean data
    yeeaah haalo!
    
    print(messy_data.replace("!","  woooaaah"))     -- replace function
        yeeaah haalo  woooaaah 
        
    print(messy_data.replace("!","  woooaaah").strip())  --replace+strip
    yeeaah haalo  woooaaah
    ```
    
    ```python
    quote_2 = 'I\'am a single quote within tha single quote'
    
    print(quote_2.split())          --split work only with spaces
    ["I'am", 'a', 'single', 'quote', 'within', 'tha', 'single', 'quote']
    
    quote_2 = 'I\'am,a,single,quote,within,tha,single,quote'
    
    print(quote_2.split())     --doesnt splited due to comma
    ["I'am,a,single,quote,within,tha,single,quote"]
    
    print(quote_2.split(","))    -- use "," to split by comma
    ["I'am", 'a', 'single', 'quote', 'within', 'tha', 'single', 'quote']
    ```
