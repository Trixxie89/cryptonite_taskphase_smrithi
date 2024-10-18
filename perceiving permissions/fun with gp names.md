# fun with gp names
so here i used id command as specified t get new name of hacker..then i used chgrp cpmmand t0  change the group ownership of a file or directory. ..then read the flag with cat
``` bash
                                                                            Connected!
hacker@permissions~fun-with-groups-names:~$ id
uid=1000(hacker) gid=1000(grp1106) groups=1000(grp1106)
hacker@permissions~fun-with-groups-names:~$ chgrp uid /flag
chgrp: invalid group: ‘uid’
hacker@permissions~fun-with-groups-names:~$ chgrp 1000 /flag
hacker@permissions~fun-with-groups-names:~$ cat /flag
pwn.college{4bGnhS_kRRqYkdAYBOMUPHUuwAB.dJzNyUDL1MjN0czW}
```
