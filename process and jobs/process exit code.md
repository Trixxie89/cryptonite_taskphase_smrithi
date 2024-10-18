# process exit code.md
When i run /challenge/get-code, it performs some action and then finishes executing.
After the command finishes,i stored  the exit code is stored in a special variable called $?. This code indicates whether the command succeeded (usually 0) or failed (any non-zero value).
I then run another command, /challenge/submit-code, and pass it the exit code you just retrieved. This tells the system what the result of the previous command was..
``` bash
                                                                            Connected!
hacker@processes~process-exit-codes:~$ /challenge/get-code
Exiting with an error code!
hacker@processes~process-exit-codes:~$ echo $?
244
hacker@processes~process-exit-codes:~$ /challenge/submit-code 244
CORRECT! Here is your flag:
pwn.college{EbueUbkHEVMUgnA-WzTqQQCmxey.dljN4UDL1MjN0czW}
```
ASKED HELP OF FRIEND FOR THIS
