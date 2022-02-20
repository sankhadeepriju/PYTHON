# While LOOP
---
It is a repeatative code block which executes a set of statements till the condition given is true.
```
i = 1
while(i<3):
    print(i)
    i+=1
```
```
#output 
1
2
```
---
>**IMPORTANT:** <p>We  can see that with the use of **_print()_** statement the control moves to next line automatically after executing a statement.</p>
    
<p>So to make the cursor print in a single line we use:</p>

```
print("hello", end="")
```
___
### HERE IS A SAMPLE PROGRAM:
```
    #initialisation
    i = 1
    j = 1
    #condition_outer_loop
    while i <= 5:
        print(" HAPPY ", end="") 
        #end="" helps to maintain the cursor in the same      #line.
        #condition_inner_loop
        while j <= 4:
            print(" BIRTHDAY ", end="")
            j+ = 1
        j = 1 #reset value of j for inner loop to repeat #again.
        i = i + 1
        print() 
        #to force the cursor to move to the next line after #each iteration of the outer loop.*/
```
```
#output
 HAPPY  BIRTHDAY  BIRTHDAY  BIRTHDAY  BIRTHDAY 
 HAPPY  BIRTHDAY  BIRTHDAY  BIRTHDAY  BIRTHDAY 
 HAPPY  BIRTHDAY  BIRTHDAY  BIRTHDAY  BIRTHDAY 
 HAPPY  BIRTHDAY  BIRTHDAY  BIRTHDAY  BIRTHDAY 
 HAPPY  BIRTHDAY  BIRTHDAY  BIRTHDAY  BIRTHDAY
 ```