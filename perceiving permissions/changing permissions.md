# changing permissions
so here i firstdid ls -l to read details of ?flag
then i did chmod o +r as per Q /..adding reading permissions to others..other than owner..then i read flag ad got it
``` bash
Connected!
hacker@permissions~changing-permissions:~$ ls -l /flag
-r-------- 1 root root 58 Oct 18 17:50 /flag

hacker@permissions~changing-permissions:~$ chmod o+r /flag
hacker@permissions~changing-permissions:~$ ls -l /flag
-r--r--r-- 1 root root 58 Oct 18 17:50 /flag
hacker@permissions~changing-permissions:~$ cat /flag
pwn.college{U9mPA3etTztrDhEFg9IF1cPK1vu.dNzNyUDL1MjN0czW}
hacker@permissions~changing-permissions:~$
```
AKED HELP OF FRIEND FOR THIS
