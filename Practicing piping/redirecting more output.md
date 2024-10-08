# REDIRECTING MORE OUTPUT
so this turned out to be the alternate condition i talked about before in the previous challenge..so here we have to run /challenge/run pgm..and it has the flag...and its coped to my flag..then i just did cat myflag..
cuase i need to take the flag...which is copied in myflag
``` bash
                                                                            Connected!
hacker@piping~redirecting-more-output:~$ /challenge/run > myflag
[INFO] WELCOME! This challenge makes the following asks of you:
[INFO] - the challenge will check that output is redirected to a specific file path : myflag
[INFO] - the challenge will output a reward file if all the tests pass : /flag

[HYPE] ONWARDS TO GREATNESS!

[INFO] This challenge will perform a bunch of checks.
[INFO] If you pass these checks, you will receive the /flag file.

[TEST] You should have redirected my stdout to a file called myflag. Checking...

[PASS] The file at the other end of my stdout looks okay!
[PASS] Success! You have satisfied all execution requirements.
hacker@piping~redirecting-more-output:~$ cat myflag

[FLAG] Here is your flag:
[FLAG] pwn.college{csg9nuLO3enMVjoxDhF-pYz2zwp.dVjN1QDL1MjN0czW}
```
