# LISTING FILES
so here its written to list all files in challenge..ie ls /challenge..from there  we get the name of new file..and we just need to execute the file (we find its exexutable from file commnd)..so write /challenge/3135-renamed-run-7409
```bash
hacker@commands~listing-files:~$ file /challenge/3135-renamed-run-7409
/challenge/3135-renamed-run-7409: setuid a /opt/pwn.college/bash script, ASCII text executable
hacker@commands~listing-files:~$  /challenge/3135-renamed-run-7409
Yahaha, you found me! Here is your flag:
pwn.college{oEFtwqatboL9sWo9WWxWGWvh9hy.dhjM4QDL1MjN0czW}
```
Asked the help of my taskphase gp mentor to understand use of file command and how to get the flag
