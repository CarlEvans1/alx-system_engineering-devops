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


