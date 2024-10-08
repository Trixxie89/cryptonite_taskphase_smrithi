# REDIRECTING OUTPUT
so here i learnt what stdout means is to take putput normally printed on screen ..its stored in aafile
so here i had to write pwn to college ..pwn is atext not a /challenge/run type of pgm..so we havve to use echo
so echo PWN > COLLEGE
``` bash
Connected!
hacker@piping~redirecting-output:~$ PWN > COLLEGE
ssh-entrypoint: PWN: command not found
You have created the COLLEGE file, but you didn't write the correct value to
it. Make sure to write PWN to the COLLEGE file.
hacker@piping~redirecting-output:~$ echo PWN > COLLEGE
Correct! You successfully redirected 'PWN' to the file 'COLLEGE'! Here is your
flag:
pwn.college{YywLvmBC94bYJm6O5I0qTyKI6jP.dRjN1QDL1MjN0czW}
hacker@piping~redirecting-output:~$
```
