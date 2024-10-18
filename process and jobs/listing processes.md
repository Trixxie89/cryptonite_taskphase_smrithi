# LISTING PROCESSES
so here i first used ps -ef and ps aux ..ps to display list of currently running processes and -e to list all processes running on the sys..-f to display in full format..where i got the name of file/challengle/4094... i ran
that and got flag
```  bash
codebind@Smrithi:~$ ssh -i ./key hacker@dojo.pwn.college
Connected!
hacker@processes~listing-processes:~$ ps -ef
UID          PID    PPID  C STIME TTY          TIME CMD
root           1       0  0 16:09 ?        00:00:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bin/dojo-init /ru
root           7       1  0 16:09 ?        00:00:00 /run/dojo/bin/sleep 6h
root          68       1  0 16:09 ?        00:00:00 /challenge/4092-run-7264
root          72      68  0 16:09 ?        00:00:00 sleep 6h
hacker        73       0  0 16:09 pts/0    00:00:00 /run/dojo/bin/ssh-entrypoint
hacker        90      73  0 16:13 pts/0    00:00:00 ps -ef
hacker@processes~listing-processes:~$ ps aux
USER         PID %CPU %MEM    VSZ   RSS TTY      STAT START   TIME COMMAND
root           1  0.0  0.0   1056   640 ?        Ss   16:09   0:00 /sbin/docker-init -- /nix/var/nix/profiles/default/bi
root           7  0.0  0.0   5052  2240 ?        S    16:09   0:00 /run/dojo/bin/sleep 6h
root          68  0.0  0.0   4132  2560 ?        S    16:09   0:00 /challenge/4092-run-7264
root          72  0.0  0.0   2744  1280 ?        S    16:09   0:00 sleep 6h
hacker        73  0.0  0.0   5372  4160 pts/0    Ss   16:09   0:00 /run/dojo/bin/ssh-entrypoint
hacker        91  0.0  0.0   7868  3200 pts/0    R+   16:13   0:00 ps aux
hacker@processes~listing-processes:~$ /challenge/4092-run-7264
Yahaha, you found me! Here is your flag:
pwn.college{Ig141ti_XqhjlsXgZmuPpVpGVMs.dhzM4QDL1MjN0czW}
Now I will sleep for a while (so that you could find me with 'ps').
```
