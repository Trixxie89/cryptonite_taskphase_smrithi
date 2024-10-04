# EXCLUSIONARY GLOBBING
so here i used first the cd directory with absolute path..but i had to change it..then i did[!pwn}
as specified in q..but i had to conider rest of elements also so i put astrid too and go it
``` bash
                                                                             Connected!
hacker@globbing~exclusionary-globbing:~$ ls /challenge/files
amazing      fantastic   kind        pwning     uplifting   zesty
beautiful    great       laughing    queenly    victorious
challenging  happy       magical     radiant    wonderful
delightful   incredible  nice        splendid   xenial
educational  jovial      optimistic  thrilling  youthful
hacker@globbing~exclusionary-globbing:~$
hacker@globbing~exclusionary-globbing:~$ /challenge/run /challenge/files [!pwn]
Error: please run with a working directory of /challenge/files!
hacker@globbing~exclusionary-globbing:~$ cd /challenge/files
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [!pwn]
Your expansion did not expand to the requested files (amazing beautiful
challenging delightful educational fantastic great happy incredible jovial kind
laughing magical optimistic queenly radiant splendid thrilling uplifting
victorious xenial youthful zesty).
Instead, it expanded to:
[!pwn]
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/files$ /challenge/run [!pwn]*
ssh-entrypoint: /challenge/files$: No such file or directory
hacker@globbing~exclusionary-globbing:/challenge/files$ cd /challenge/files
hacker@globbing~exclusionary-globbing:/challenge/files$ /challenge/run [!pwn]*
You got it! Here is your flag!
pwn.college{0CnNEOL866TJRoJfMNdA6T_JXBg.dZjM4QDL1MjN0czW}
```
