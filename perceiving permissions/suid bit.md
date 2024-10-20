# SUID BIT
i first used chmod  to chage permissions of file...u+S indicated changing user permissions..+s sets suid bit...ls to get details..then i ran challenge
  ``` bash

hacker@permissions~the-suid-bit:~$ chmod u+s /challenge/getroot
hacker@permissions~the-suid-bit:~$ ls -l /challenge/getroot
-rwsr-xr-x 1 root root 155 Jul 12 10:30 /challenge/getroot
hacker@permissions~the-suid-bit:~$
hacker@permissions~the-suid-bit:~$  /challenge/getroot
SUCCESS! You have set the suid bit on this program, and it is running as root!
Here is your shell...
root@permissions~the-suid-bit:~# cat /flag
pwn.college{cizrqiUdogUvKHlxjkHENM9eQPC.dNTM2QDLzkjN0czW}
```
