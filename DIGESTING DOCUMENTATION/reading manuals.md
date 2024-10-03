# reading manuals
So here it was taught about man command ..which gives us a manual or info about command give as argument and it is stored in 
/usr/share/man directory,so i just typed man challenge
got the manual for the challenge..in it one condition was to print flag put -wfmntl NUM where num must be 298..so i did
like 1st challenge where we put challenge/challenge and then argument and i got flag( we are invoking special feature with argument
and here special feature is flag)
``` bash
hacker@man~reading-manuals:~$ man challenge

CHALLENGE(1)                  Challenge Commands                 CHALLENGE(1)

NAME
       /challenge/challenge - print the flag!

SYNOPSIS
       challenge OPTION

DESCRIPTION
       Output the flag when called with the right arguments.

       --fortune
              read a fortune

       --version
              output version information and exit

       --wfmntl NUM
              print the flag if NUM is 298

AUTHOR
       Written by Zardus.

REPORTING BUGS
       The repository for this dojo: <https://github.com/pwncollege/linux-lu‐
       minarium/>

SEE ALSO
       man(1) bash-builtins(7)

pwn.college                        May 2024                      CHALLENGE(1)
hacker@man~reading-manuals:~$ challenge option
ssh-entrypoint: challenge: command not found
hacker@man~reading-manuals:~$ /challenge/challenge --wfmntl NUM
Incorrect usage! Please read the challenge man page!
hacker@man~reading-manuals:~$  /challenge/challenge --wfmntl 298
Correct usage! Your flag: pwn.college{wHf2MC98mSEnt-ld6OPWwEQrErc.dRTM4QDL1MjN0czW}
hacker@man~reading-manuals:~$
```

