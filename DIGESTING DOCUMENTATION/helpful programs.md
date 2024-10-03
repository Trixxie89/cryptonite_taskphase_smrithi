# HELPFUL PROGRAMS
here i used /challenge/challenge --help..from the descriotionn..printed the value for the -g argument ..basially i did according 
t hint provided to me
``` bash
                                                                               Connected!
hacker@man~helpful-programs:~$ --help
ssh-entrypoint: --help: command not found
hacker@man~helpful-programs:~$ /challenge/challenge --help
usage: a challenge to make you ask for help [-h] [--fortune] [-v]
                                            [-g GIVE_THE_FLAG] [-p]

optional arguments:
  -h, --help            show this help message and exit
  --fortune             read your fortune
  -v, --version         get the version number
  -g GIVE_THE_FLAG, --give-the-flag GIVE_THE_FLAG
                        get the flag, if given the correct value
  -p, --print-value     print the value that will cause the -g option to give
                        you the flag
hacker@man~helpful-programs:~$ /challenge/challenge --print-value
The secret value is: 812
hacker@man~helpful-programs:~$ /challenge/challenge --give-the-flag
usage: a challenge to make you ask for help [-h] [--fortune] [-v]
                                            [-g GIVE_THE_FLAG] [-p]
a challenge to make you ask for help: error: argument -g/--give-the-flag: expected one argument
hacker@man~helpful-programs:~$ /challenge/challenge -g 812
Correct usage! Your flag: pwn.college{UbudA8L1vvd2nywp5uK5kmUa6Rk.ddjM4QDL1MjN0czW}
