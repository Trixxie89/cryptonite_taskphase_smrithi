# HIDDEN FILES
first i used ls -a..it gave me some dot files but it wasnt flag..then i chwcked Q and it was given the flag file was in /..so i tried ls -a / ..nd BINGO I got it..
``` bash
hacker@commands~hidden-files:~$ ls -a
.   .ICEauthority  .bash_logout  .cache   .dbus   .mozilla  Desktop  q
..  .bash_history  .bashrc       .config  .local  .profile  p
hacker@commands~hidden-files:~$ ls -a /
.   .dockerenv             bin   challenge  etc   lib    lib64   media  nix  proc  run   srv  tmp  var
..  .flag-278181202011930  boot  dev        home  lib32  libx32  mnt    opt  root  sbin  sys  usr
hacker@commands~hidden-files:~$ cat /.flag-278181202011930
pwn.college{4c7z6eLI9G2PcIkX0lA6JL7uQbt.dBTN4QDL1MjN0czW}
hacker@commands~hidden-files:~$
```
