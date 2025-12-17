# OverTheWire Bandit – Level 11 → Level 12

**Goal**
The password for the next level is stored in the file data.txt, where all the letters have been rotated by 13 positions.


**Connection**
ssh bandit11@bandit.labs.overthewire.org -p 2220
# Password: dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

**Solution**
bandit11@bandit:~$ ls
data.txt
bandit11@bandit:~$ cat data.txt
Gur cnffjbeq vf 7k16JArUVv5LxVuJfsSVdbbtaHGlw9D4
bandit11@bandit:~$ cat data.txt | tr 'A-Za-z' 'N-ZA-Mn-za-m'
The password is 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
