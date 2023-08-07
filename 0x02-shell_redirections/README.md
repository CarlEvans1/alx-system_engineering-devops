0. Hello World
#!/bin/bash
echo "Hello, World"

1. Confused smiley
#!/bin/bash
echo '"(Ôo)'\'

2. Let's display a file
#!/bin/bash
cat /etc/passwd

3. What about 2?
#!/bin/bash
cat /etc/passwd /etc/hosts

4. Last lines of a file
#!/bin/bash
tail -n 10 /etc/passwd

5. I'd prefer the first ones actually
#!/bin/bash
head -n 10 /etc/passwd

6. Line #2
#!/bin/bash
head -n 3 iacta | tail -n 1

7. It is a good file that cuts iron without making a noise
#!/bin/bash
echo "Best School" > \\\*\\\\"'\"Best School\"\\'"\\\\\*\$\\\?\\\*\\\*\\\*\\\*\\\*\:\)

8. Save current state of directory
#!/bin/bash
ls -la > ls_cwd_content

9. Duplicate last line
#!/bin/bash
tail -n 1 iacta >> iacta

10. No more javascript
#!/bin/bash
find . -type f -name "*.js" -delete

11. Don't just count your directories, make your directories count
#!/bin/bash
find . -type d -not -name '.' | wc -l

12. What’s new
#!/bin/bash
ls -t1 | head -n 10

13. Being unique is better than being perfect
#!/bin/bash
sort | uniq -u

14. It must be in that file
#!/bin/bash
grep -i "root" /etc/passwd


