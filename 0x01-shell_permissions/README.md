0. My name is Betty
#!/bin/bash
su betty

1. Who am I
#!/bin/bash
whoami

2. Groups
#!/bin/bash
groups

3. New owner
#!/bin/bash
sudo chown betty hello

4. Empty!
#!/bin/bash
touch hello

5. Execute
#!/bin/bash
chmod u+x hello

6. Multiple permissions
#!/bin/bash
chmod u+x,g+x,o+r hello

7. Everybody!
#!/bin/bash
chmod ugo+x hello

8. James Bond
#!/bin/bash
chmod 007 hello

9. John Doe
#!/bin/bash
chmod 753 hello

10. Look in the mirror
#!/bin/bash
chmod --reference=olleh hello

11. Directories
#!/bin/bash
chrmod a+x *

