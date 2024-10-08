# PIPING REDIRECTING OUTPUT
so here i had to use < which is for stdin..so here /challenge/run had tp tke inp..PWN..But condition is PWN must have
college..in it//so o first echoed college to pwn..and then used < and got flag
``` bash
Connected!
hacker@piping~redirecting-input:~$ /challenge/run > PWN
hacker@piping~redirecting-input:~$ echo COLLEGE >> PWN
hacker@piping~redirecting-input:~$ cat PWN
You have not redirected anything to my standard input. Please do so, using '<'.
COLLEGE
hacker@piping~redirecting-input:~$ /challenge/run < PWN
Reading from standard input...
Your PWN file must have the value 'COLLEGE', but I instead read: You have not
redirected anything to my standard input. Please do so, using '<'.
hacker@piping~redirecting-input:~$ echo COLLEGE > PWN
hacker@piping~redirecting-input:~$  /challenge/run < PWN
Reading from standard input...
Correct! You have redirected the PWN file into my standard input, and I read
the value 'COLLEGE' out of it!
Here is your flag:
pwn.college{wCxjuunna8cIIIc0WC6PAOWhncT.dBzN1QDL1MjN0czW}
```
