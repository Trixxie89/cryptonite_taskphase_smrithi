# BECOMING ROOTS WITH SU
``` bash
hacker@users~becoming-root-with-su:~$ ls -l /usr/bin/su
-rwxr-xr-x 1 root root 67816 Apr  9  2024 /usr/bin/su
hacker@users~becoming-root-with-su:~$ su -
Password:
su: Authentication failure
hacker@users~becoming-root-with-su:~$ su
Password:
root@users~becoming-root-with-su:/home/hacker# ls
COLLEGE  PWN           m       not-the-flag  q         w
Desktop  instructions  myflag  p             the-flag
root@users~becoming-root-with-su:/home/hacker# cat /the-flag
cat: /the-flag: No such file or directory
root@users~becoming-root-with-su:/home/hacker# ;cat the-flag
bash: syntax error near unexpected token `;'
root@users~becoming-root-with-su:/home/hacker# cat the-flag
 |
\|/ This is the first half:
 v
pwn.college{k8T9XIvKijH_FOklFoUBMB52Ofv.ddDM5QDL1MjN0czW}
                              ^
     that is the second half /|\
                              |

If you only see the second half above, you redirected in *truncate* mode (>)

rather than *append* mode (>>), and so the write of the second half to stdout
overwrote the initial write of the first half directly to the file. Try append
mode!
root@users~becoming-root-with-su:/home/hacker# cat not-the-flag
pwn.college{MBjfuKorJhqnizp4pKQtV-1VLI1.dVTN0UDL1MjN0czW}
root@users~becoming-root-with-su:/home/hacker#
```
