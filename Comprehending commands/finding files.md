# FINDING FILES
here i used fimd command for the root directory according to suntax and got the files...the first file came waas
/usr/lib/python3.8/concurrent/flag..i used cat of this ..i got it..it actually would have been triala and error if i didnt get first itself..
``` bash
                                                                            Connected!
hacker@commands~finding-files:~$ find / -name flag
find: ‘/tmp/tmp.MiOQGWw5Zc’: Permission denied
find: ‘/etc/ssl/private’: Permission denied
/usr/lib/python3.8/concurrent/flag
/usr/local/lib/python3.8/dist-packages/pwnlib/flag
/usr/local/share/radare2/5.9.5/flag
find: ‘/var/cache/apt/archives/partial’: Permission denied
find: ‘/var/cache/ldconfig’: Permission denied
find: ‘/var/cache/private’: Permission denied
find: ‘/var/lib/apt/lists/partial’: Permission denied
find: ‘/var/lib/mysql-files’: Permission denied
find: ‘/var/lib/private’: Permission denied
find: ‘/var/lib/mysql’: Permission denied
find: ‘/var/lib/mysql-keyring’: Permission denied
find: ‘/var/lib/php/sessions’: Permission denied
find: ‘/var/log/private’: Permission denied
find: ‘/var/log/apache2’: Permission denied
find: ‘/var/log/mysql’: Permission denied
find: ‘/run/mysqld’: Permission denied
find: ‘/run/sudo’: Permission denied
find: ‘/root’: Permission denied
/opt/pwndbg/.venv/lib/python3.8/site-packages/pwnlib/flag
/opt/radare2/libr/flag
find: ‘/proc/tty/driver’: Permission denied
find: ‘/proc/1/task/1/fd’: Permission denied
find: ‘/proc/1/task/1/fdinfo’: Permission denied
find: ‘/proc/1/task/1/ns’: Permission denied
find: ‘/proc/1/fd’: Permission denied
find: ‘/proc/1/map_files’: Permission denied
find: ‘/proc/1/fdinfo’: Permission denied
find: ‘/proc/1/ns’: Permission denied
find: ‘/proc/8/task/8/fd’: Permission denied
find: ‘/proc/8/task/8/fdinfo’: Permission denied
find: ‘/proc/8/task/8/ns’: Permission denied
find: ‘/proc/8/fd’: Permission denied
find: ‘/proc/8/map_files’: Permission denied
find: ‘/proc/8/fdinfo’: Permission denied
find: ‘/proc/8/ns’: Permission denied
hacker@commands~finding-files:~$ cat /usr/lib/python3.8/concurrent/flag
pwn.college{cbqheGUgSt9QzkRizO0eO_YR1Qi.dJzM4QDL1MjN0czW}hacker@commands~finding-files:~$
```
