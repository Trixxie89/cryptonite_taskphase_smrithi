# PIPING WRITING TO MULTIPLE PGM
This was a straight forward Q..so here 1 i have to use () for one of the commands..so i put and got it.
``` bash

              Connected!
hacker@piping~writing-to-multiple-programs:~$ /challenge/hack | tee > /challenge/the  | /challenge/planet
ssh-entrypoint: /challenge/the: Permission denied
Are you sure you're properly redirecting input into '/challenge/planet'?
hacker@piping~writing-to-multiple-programs:~$  /challenge/hack | tee > (/challenge/planet)  | /challenge/the
ssh-entrypoint: syntax error near unexpected token `('
hacker@piping~writing-to-multiple-programs:~$  /challenge/hack | tee > ( /challenge/planet)  | /challenge/the
ssh-entrypoint: syntax error near unexpected token `('
hacker@piping~writing-to-multiple-programs:~$  /challenge/hack | tee >( /challenge/planet)  | /challenge/the
Congratulations, you have duplicated data into the input of two programs! Here
is your flag:
pwn.college{wqluWuXEpwnMtX9FfgQchX2yS19.dBDO0UDL1MjN0czW}
hacker@piping~writing-to-multiple-programs:~$ ls /challenge
DESCRIPTION.md  bin  hack  planet  the
Congratulations, you have duplicated data into the input of two programs! Here
is your flag:
pwn.college{wqluWuXEpwnMtX9FfgQchX2yS19.dBDO0UDL1MjN0czW}
hacker@piping~writing-to-multiple-programs:~$

```
