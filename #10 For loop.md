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