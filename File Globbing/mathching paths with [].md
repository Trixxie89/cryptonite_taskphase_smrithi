# MATCHING WITH PATHS []
so first i changed director and started executing but i needed to use home directory itself ..so i used cd~
then i ran the command /challenge/run and put /challenge/files/file_[bash}..hust like/home/hacker/file_[ab]
given in Q 
``` bash
hacker@globbing~matching-paths-with-:/challenge/files$ cd ~
hacker@globbing~matching-paths-with-:~$ cd /challenge/files
hacker@globbing~matching-paths-with-:/challenge/files$ /challenge/run file_[bahs]
Error: please run with a working directory of /home/hacker!
hacker@globbing~matching-paths-with-:/challenge/files$ cd ~
hacker@globbing~matching-paths-with-:~$ /challenge/run /challenge/files/file_[bahs]
You got it! Here is your flag!
pwn.college{kVbk4aAqMg5aD57Bzr_8CVI2iym.dRjM4QDL1MjN0czW}
hacker@globbing~matching-paths-with-:~$
```
