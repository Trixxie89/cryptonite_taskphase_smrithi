# adding commands
``` bash
                                                                            Connected!
hacker@path~adding-commands:~$ echo $PATH
/run/challenge/bin:/run/workspace/bin:/usr/local/sbin:/usr/local/bin:/usr/sbin:/usr/bin:/sbin:/bin
hacker@path~adding-commands:~$ which cat
/run/workspace/bin/cat
hacker@path~adding-commands:~$ nano win
hacker@path~adding-commands:~$ chmod +x win
hacker@path~adding-commands:~$ mkdir ~/my_commands
mv win ~/my_commands/
hacker@path~adding-commands:~$ PATH=~/my_commands:$PATH
hacker@path~adding-commands:~$ /challenge/run
Invoking 'win'....
pwn.college{gwmC_3KZgLAOAEN6UJzeyhk4H_w.dZzNyUDL1MjN0czW}
```
