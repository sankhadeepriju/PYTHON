>**BREAK**:
<p>The break statement helps to exit a block ignoring all the remaining statements of the same block.

**<p style="text-align: center;">BREAK STATEMENT EXITS THE LOOP PERMANENTYLY</p>**

```
i=1
while i<6:
    if i==4:
        break
        #nothing from this point will be executed when i=4.
    print(i)
    i+=1
print('bye')
```
```
#output
1
2
3
bye
```
___
>**CONTINUE**:
<p>The continue statement helps to skip the block ignoring all the remaining statements of the same block and begin execution from the next iteration.</p>


**<p style="text-align: center;">CONTINUE STATEMENT EXITS THE LOOP ONLY FOR THE GIVEN ITERATION </p>**
```
i=1
while i<11:
    if i%2==0:
        i += 1
        continue
    else:
        print(i)
        i+=1
print('bye')
```
```
#output
1
3
5
7
9
```
---
>**PASS**:
<p>The pass statement is used in an empty block when we have nothing to write.
```
for i in range(1,11):
    if(i%2!=0):
        pass
        #EMPTY BLOCK
    else:
        print(i)
print("BYE")
```
```
#output
2
4
6
8
10
BYE
```