# help-for-builtins
Here i first used help with challenge and found the description sayinh how t procceed..i just learnt
the fact that for bulletin i dont have to specify the path only the bulletin name is required and i gave argument with value given
```` bash
          Connected!
hacker@man~help-for-builtins:~$ help challenge
challenge: challenge [--fortune] [--version] [--secret SECRET]
    This builtin command will read you the flag, given the right arguments!

    Options:
      --fortune         display a fortune
      --version         display the version
      --secret VALUE    prints the flag, if VALUE is correct

    You must be sure to provide the right value to --secret. That value
    is "cNnYvhL1".
hacker@man~help-for-builtins:~$ /challenge/challenge --secret cNnYvhL1
ssh-entrypoint: /challenge/challenge: No such file or directory
hacker@man~help-for-builtins:~$ challenge --secret cNnYvhL1
Correct! Here is your flag!
pwn.college{cNnYvhL1aZk2QBFVop3qX45gJ-P.dRTM5QDL1MjN0czW}
```
the rseource i used was llike when i asked syntax for shell bulletin with argument..the AI overview of google
gave me an..theres no link for tjat..so i will just post the sentences i referred to
To pass an argument to a Linux shell script, you can write the argument after the script name,
 separated by a space. For example, to pass an argument named my_argument to the script ./script.sh,
you would type ./script.sh my_argument

