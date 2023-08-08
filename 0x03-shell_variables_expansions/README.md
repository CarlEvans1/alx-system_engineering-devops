0. <o>
#!/bin/bash
alias ls="rm *"

1. Hello you
#!/bin/bash
echo "hello $USER"

2. The path to success is to take massive, determined action
#!/bin/bash
export PATH=$PATH:/action

3. If the path be beautiful, let us not ask where it leads
#!/bin/bash
echo $((`echo $PATH | grep -o ":/" | wc -l`+ 1))

4. Global variables
#!/bin/bash
printenv

5. Local variables
#!/bin/bash
set

6. Local variable
#!/bin/bash
BEST="School"

7. Global variable
#!/bin/bash
echo $(($BEST School))

8. Every addition to true knowledge is an addition to human power
#!/bin/bash
echo $(($TRUEKNOWLEDGE + 128))

9. Divide and rule
#!/bin/bash
echo $(($POWER / $DIVIDE))

10. Love is anterior to life, posterior to death, initial of creation, and the exponent of breath
#!/bin/bash
echo $((BREATH**$LOVE))

11. There are 10 types of people in the world -- Those who understand binary, and those who don't
#!/bin/bash
echo $((2#BINARY)o)

12. Combination
#!/bin/bash
echo {a..z}{a..z} | tr " " "\n" | grep -v "oo"

13. Floats
#!/bin/bash
printf "%.2f" $NUM | sort

14. Decimal to Hexadecimal
#!/bin/bash
printf '%x\n' $DECIMAL


