# the path variable
so here it was asked stop rm command from diexecuting.this can be done by removing the directory of rm from PATH..Aas it contains the ist of directories..so i did PATH="" as given an example,this destroys all directories in path including rm..and then i ran the challenge nad got it...we can also do export PATH=""
``` bash
Connected!
hacker@path~the-path-variable:~$ echo $PATH
/run/challenge/bin:/run/workspace/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
hacker@path~the-path-variable:~$ PATH=""
hacker@path~the-path-variable:~$ /challenge/run
Trying to remove /flag...
/challenge/run: line 4: rm: No such file or directory
The flag is still there! I might as well give it to you!
pwn.college{oSfODtPMmiN-NXPsRcZGdjl1q3E.dZzNwUDL1MjN0czW}
```
