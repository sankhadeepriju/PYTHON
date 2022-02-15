>DATA TYPE
* **NONE** : a variable associated with no value.
* **NUMERIC**
    * int
    * float
    * complex
    * bool
* **TYPE CONVERSION**
    * int to float and vice-versa
    
        ```
        a = 6

        b = float(b)
        ```

        **output: 6.0**

        ```
        x = 7.2
        
        y = int(x)
        ```

        **output: 7**
    * complex no. can be used using func. **complex(a,b)** 
        output: a+bj
    * bool

        It is a data type to obtain results in **TRUE/FALSE**.
        
        example: c = a < y , OUTPUT: TRUE.

        In TYPE CONVERSION, TRUE=1 & FALSE=0.


* **SEQUENCE**
    * LIST --> []
    * TUPLE --> ()
    * SET --> {}
    * STRING --> " " or ' '
    * RANGE --> data type used to print a sequence from a   beginning point to a end point.
* **DICTIONARY OR MAPPING**
    
    EACH ELEMENT CAN BE UNIQUELY MAPPED USING A RESPECTIVE KEY ATTACHED.
    
    **KEYS SHOULD BE UNIQUE AND ITS SMART TO USE THEM IN SET, i.e curly braces { }**.
    
    Ex:

    ``` 
        dict={1:'a',2:'b',3:'c'}
        dict.keys()
        dict.values()
    ```
    dict.keys() points out the keys.
    
    dict.values() points out the values only.

    To fetch a particular value using key:

    ```
    dict[1]
    dict.get(2)
    ```
    dict[1] and dict.get(2) helps fetching values associated with the given keys.
