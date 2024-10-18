# KILLING PROCESSES
Kil command is used to terminate proceeses..so here i did like in example..used grep command first//and got argument for kill ie 73...then did kill 73..and ran /challenge/run
``` bash
Connected!
hacker@processes~killing-processes:~$ ps -ef | grep dont_run
hacker        73      71  0 16:20 ?        00:00:00 /challenge/dont_run
hacker        93      75  0 16:20 pts/0    00:00:00 grep --color=auto dont_run
hacker@processes~killing-processes:~$ kill 73
hacker@processes~killing-processes:~$ /challenge/run
Great job! Here is your payment:
pwn.college{gfrHVaMqy9yi1EYCfPsB0n4XOkr.dJDN4QDL1MjN0czW}
```
