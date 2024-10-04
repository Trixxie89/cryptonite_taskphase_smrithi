# MATCHING WITH []
so here i understood [] used for multiple arguments..like it can be abch...so hee it was given file coud be a,b,h,s so i put those in paranthesis and ran program..but i fased problem as 
first i forgot that to call file u dont need to put / before this..as / used for directory
..so i had to look up t the syntax agin
``` bash
                                                                            Connected!
hacker@globbing~matching-with-:~$ ls /challenge/files
file_a  file_d  file_g  file_j  file_m  file_p  file_s  file_v  file_y
file_b  file_e  file_h  file_k  file_n  file_q  file_t  file_w  file_z
file_c  file_f  file_i  file_l  file_o  file_r  file_u  file_x
hacker@globbing~matching-with-:~$ cd /challenge/files
hacker@globbing~matching-with-:/challenge/files$ ls file_[ash]
file_a  file_h  file_s
hacker@globbing~matching-with-:/challenge/files$ /challenge/run
Error: you did not use a square bracket glob...
hacker@globbing~matching-with-:/challenge/files$ ls /challenge/run/file_[abssh]
ls: cannot access '/challenge/run/file_[abssh]': Not a directory
hacker@globbing~matching-with-:/challenge/files$ ls /challenge/run file_[absh]
/challenge/run  file_a  file_b  file_h  file_s
hacker@globbing~matching-with-:/challenge/files$ /challenge/run file_[bah]
Your expansion did not expand to the requested files (file_a, file_b, file_h,
and file_s). Instead, it expanded to:
file_a file_b file_h
hacker@globbing~matching-with-:/challenge/files$ /challenge/run file_[bahs]
You got it! Here is your flag!
pwn.college{g4mtOf_-qHvn71kn5yuKVO-WVAv.dNjM4QDL1MjN0czW}
hacker@globbing~matching-with-:/challenge/files$
```
