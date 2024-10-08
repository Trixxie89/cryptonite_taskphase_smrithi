# linking files








``` bash
Connected!
hacker@commands~linking-files:~$  cat /flag
cat: /flag: Permission denied
hacker@commands~linking-files:~$ ln -s /flag /home/hacker/not-the-flag
hacker@commands~linking-files:~$ file /home/hacker/not-the-flag
/home/hacker/not-the-flag: symbolic link to /flag
hacker@commands~linking-files:~$ /challenge/catflag
About to read out the /home/hacker/not-the-flag file!
pwn.college{gr0j0nDju_KvV_E-xPJ0M7q-BoA.dlTM1UDL1MjN0czW}
```
