# adding commands
so in this i first used which cat to find the directory where cat file is located ..then to create the scriot i typed nanao win..in that i typed #!/bin/bash
/bin/cat /flag.. This line uses the absolute path to the cat command to read the contents of the /flag file...then i saved it..and did chmod to make it executable...created mt_command directory..transfered win to my commands using mv..then i made that the path as it has win file..the i ran challenge and got it/

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
ASKED A FRIENDS HELP FOR THIS
