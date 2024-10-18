# SUSPENDING PROCESSES
so here i ran /challenge/run and pressed ctrl +z ..and then again ran /challenge/run..and got flag
``` bash
Connected!
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root          82      65  0 16:27 pts/0    00:00:00 bash /challenge/run
root          84      82  0 16:27 pts/0    00:00:00 ps -f

I don't see a second me!

To pass this level, you need to suspend me and launch me again! You can
background me with Ctrl-Z or, if you're not ready to do that for whatever
reason, just hit Enter and I'll exit!
^Z
[1]+  Stopped                 /challenge/run
hacker@processes~suspending-processes:~$ /challenge/run
I'll only give you the flag if there's already another copy of me running in
this terminal... Let's check!

UID          PID    PPID  C STIME TTY          TIME CMD
root          82      65  0 16:27 pts/0    00:00:00 bash /challenge/run
root          89      65  0 16:28 pts/0    00:00:00 bash /challenge/run
root          91      89  0 16:28 pts/0    00:00:00 ps -f

Yay, I found another version of me! Here is the flag:
pwn.college{sAMWww-dL1JgVCtd4FeXLL2J_v-.dVDN4QDL1MjN0czW}
hacker@processes~suspending-processes:~$

```
