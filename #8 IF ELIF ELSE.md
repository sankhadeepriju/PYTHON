# CONDITIONAL STATEMENTS
* **If**
    This conditional statement works like based on True/False situation.
    If the condition given is **TRUE**, then the associated block is executed.


    **IF Statement IS ALWAYS TERMINATED WITH A COLON.**

    ```
    if (True):
        print("I'm right")
       print("End")
    ```
    In this code, the If block only executes **I'm right** and not the **End** statement.
    That is because IF-ELSE statement in PYTHON depends on Indentation.
    When a If block starts with a certain Indentation the whole of IF block that is associated must be in the same order of Indentation.


    Multiple IF blocks can be written to keep checking for desired conditions.

* **IF ELSE**
    If the condition given is **TRUE**, then the associated block is executed. Otherwise it checks the Else block.
    ```
    if (x%2==0):
        print("EVEN")
    else
        print("ODD")
    ```
    In this code, the execution is done based on checking just the If statement. If the statement is true then the block is executed otherwise it skips all iterations and follows the else block.

* **IF-ELIF-ELSE**
    Its a smarter way to write multiple IF statements.
    In this kindof code the compiler checks for the condition one after another unless it arrives at the desired TRUE CONDITION.
    ```
    if (a==1):
        print("MONDAY")
    elif (a==2):
        print("TUESDAY")
    elif (a==3):
        print("WEDNESDAY")
    elif (a==4):
        print("THURSDAY")
    elif (a==5):
        print("FRIDAY")
    else:
        print("HOLIDAYS")
    ```
    If no condition is satisfied the compiler executes the else block.