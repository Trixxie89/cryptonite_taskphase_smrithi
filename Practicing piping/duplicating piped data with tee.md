# duplicating-piped-data-with-tee
so here
``` bash
                                                                            Connected!
hacker@piping~duplicating-piped-data-with-tee:~$ /challenge/pwn | tee /challenge/run_ouput | /challenge/college
Processing...
The input to 'college' does not contain the correct secret code! This code
should be provided by the 'pwn' command. HINT: use 'tee' to intercept the
output of 'pwn' and figure out what the code needs to be.
hacker@piping~duplicating-piped-data-with-tee:~$  cat /challenge/run_ouput
Usage: /challenge/pwn --secret [SECRET_ARG]

SECRET_ARG should be "gAY8ucLH"
hacker@piping~duplicating-piped-data-with-tee:~$  /challenge/pwn --secret gAY8ucLH | tee /challenge/run_ouput | /challenge/college
Processing...
WARNING: you are overwriting file /challenge/run_ouput with tee's output...
Correct! Passing secret value to /challenge/college...
Great job! Here is your flag:
pwn.college{gAY8ucLHjY4AWTrNAQ9XZorXO1D.dFjM5QDL1MjN0czW}
```
