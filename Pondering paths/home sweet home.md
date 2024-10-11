# HOME SWEET HOME
Took me some time to solve this one.so here we learn ~ refers to home directory which is home /hacker
so to make it the cwd we do cd ~
now according to Q we need to write the flag that would be genrated by the pgm stored in  /challenge/run(stored internally in it and displayed when we get
the right command) and write the argument in such a way the flag is copied to file..stored in ~...the hint was use the absolute path
and keep argument less than 3 char..so challenge/run to run the pgm ..then i typed ~/p..this is argument telling them 
to store the flag in that P file in ~
```bash
Writing the file to /home/hacker/q!
... and reading it back to you:
pwn.college{QowDRUIcLZ5cELN_trQt3mM0gsB.dNzM4QDL1MjN0czW}```
I learnt the fact that when we type a file path s argument after the command ..that it copies the flag to the file
if its not created ..it ill create and write it
https://www.ibm.com/docs/en/aix/7.2?topic=directories-copying-cp-command
