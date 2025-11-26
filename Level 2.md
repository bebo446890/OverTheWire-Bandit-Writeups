# OverTheWire Bandit – Level 2 → Level 3

**Goal**  
The password is stored in a file called "spaces in this filename". The file name contains multiple spaces.

**Connection**
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
# Password: 263JGJPfgU6LtdEvgfWU1XP5yac29mFx

Solution

bandit2@bandit:~$ ls -la
-rw-r----- 1 bandit3 bandit2 33 ... spaces in this filename

bandit2@bandit:~$ cat "spaces in this filename"
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
