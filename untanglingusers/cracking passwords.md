# cracking passwords
``` bash
hacker@users~cracking-passwords:~$ john --show /challenge/shadow-leak
hacker:NO PASSWORD:20000:0:99999:7:::
zardus:aardvark:20014:0:99999:7:::

2 password hashes cracked, 0 left
hacker@users~cracking-passwords:~$ su zardus
Password:
zardus@users~cracking-passwords:/home/hacker$ /challenge/run
Congratulations, you have become Zardus! Here is your flag:
pwn.college{kW5DF0Ki3Wo8uXP0oj2VUS-qjlO.ddTN0UDL1MjN0czW}
```
