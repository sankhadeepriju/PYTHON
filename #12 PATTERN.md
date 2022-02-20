**<p style="text-align:center;">Pattern1</p>**
```
print
####
####
####
####
```
```
i=1
j=1
while i<=4:
    print('#',end='')
    while j<=3:
        print('#',end='')
        j+=1
    i+=1
    j=1
    print()

#smarter
for i in range(4):
    for j in range(4):
        print('#',end='')
    print()
```
**<p style="text-align:center;">Pattern2</p>**
```
print
####
###
##
#
```
```
t=4
for i in range(4):
    for j in range(t):
        print('#',end='')
    t-=1
    print()
```
**<p style="text-align:center;">Pattern3</p>**
```
print
#
##
###
####
```
```
for i in range(4):
    for j in range(i+1):
        print('#',end='')
    t-=1
    print()
```