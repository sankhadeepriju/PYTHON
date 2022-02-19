# FOR LOOP

**This loop structure works in sequence without a test condition.**
___
>JUST LIKE IF-ELIF-ELSE,FOR LOOP CAN ALSO BE USED IN NESTED FORMATS TO PRINT PATTERNS AND ACHIEVE CERTAIN GOALS

It is usually used with **SEQUENCE DATA TYPE** to handle each values contained.
```
x=['hi','hello,'bye']
for i in x:
    print(i)
print("END")
```
```
#output
hi
hello
bye
END
```
___
>FOR LOOP with String data.
```
x="HELLO WORLD"
for i in x:
    print(i)
print("END")
```
```
#output
H
E
L
L
O
 
W
O
R
L
D
END
```
___
To print first 10 nos.
```
for i in range(1,11):
    print(i)
print('END')
```
To print first 10 odd nos.
```
for i in range(1,20,2):
    print(i)
print('END')
```


## List

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

### List comprehension method

In python, if we create a list and try to assign it to another variable, the address of the variable is assignd to the new variable. So if we try to change the value of element in the new list, the value from original list will also be changed.

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