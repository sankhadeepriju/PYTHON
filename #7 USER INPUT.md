# USER INPUT
* use the keyword _input()_ to take values from the user.
    
    **REMEMBER: input() command takes input as a String value**

EX:
```
x=input("ENTER A NO.")
y=input("ENTER A NO.")
z= x+y
print(z)

#sample input 8,9
#This will result in 89
```
So, we can avoid this situation using **EXPLICIT TYPE CONVERSION**.
```
x=input("ENTER A NO.")
y=input("ENTER A NO.")
a=int(x)
b=int(y)
z = a+b
print(z)

#sample input 8,9
#This will result in 17
The explicit conv. can be easily done in single line:
x=int(input("Enter a no."))
```
THERE'S NO CONCEPT OF ACCEPTING SINGLE CHARACTER.
So, to have such control we can make use of **index value** to print our desired character.
```
ch=input('Enter a char')
print(ch[0])
```
>**SMARTER METHOD:**
```
ch=input('Enter a char')[0]
print(ch)
```
Here the first line fetches the total string for _input_ but only associates the first index of the string to '_ch_'.


We can evaluate a complete value of an expression using the keyword **eval**.

```
ans=eval(input('Enter an expression'))
print(ans)
#sample input 1+1-1
#sample output 1
```
