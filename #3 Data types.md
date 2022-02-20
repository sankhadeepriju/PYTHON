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

* ## List

    **Properities:** 
    1. A list can store different data types.
    2. It can be accessed using index values
    3. It follow the order in which the elements are stored in it.
    4. The index of any iterable of python also accepts negetive values. Example, lst = [1, 2, 3, 4], then lst[-1] returns the last element of the list which is 4.

    ### List splitting

    If we have of a list with 10 values, we want elements from index 2 to 7, we use the below code

    ```
    lst = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10];
    lst1 = lst[2:8] # if we give 2:8, we get elements from 2 to 7
    lst2 = lst[5:] # we get elemnts from index 5 to 9
    lst3 = lst[1:8:2] 
    # will return, values from index 1 o 7, with an interval of 2, so output is [2, 4, 6, 8]
    ```

    ### **List comprehension method**

    In python, if we create a list and try to assign it to another variable, the address of the variable is assignd to the new variable. So if we try to change the value of element in the new list, the value from original list will also be changed.
___
    Practical example:
<img align='right' src='imgs/ListComprehensionMethod.png' height=160>

```
lst = [1, 2, 3, 4]
lst1 = lst
lst1[0] = 5
print(lst) # output: [5, 2, 3, 4]
```
So, we use list comprehension method to easily copy a list from another, except list comprehension method is not fast compared to other methods, but easy.
```
lst = [1, 2, 3, 4]
lst1 = [i for i in lst]
print(lst1) # output: [1, 2, 3, 4], address of this list is not as same as lst
```


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
