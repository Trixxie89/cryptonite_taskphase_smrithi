# GROUPS AND FILES
first i read did details of ?flag with ls -l then i did chgrp.. This command changes the group of the file /flag to hacker..is what i learnt..i did like in example..and go t it
``` bash                                                                            Connected!
hacker@permissions~groups-and-files:~$ ls -l /flag
-r--r----- 1 root root 58 Oct 18 17:38 /flag
hacker@permissions~groups-and-files:~$ chgrp hacker /flag
hacker@permissions~groups-and-files:~$ cat /flag
pwn.college{43-qkEM5L4jzpVY-dy1Uiy23en-.dFzNyUDL1MjN0czW}
```
