# OverTheWire Bandit – Level 7 → Level 8

**Goal**
The password for the next level is stored in the file data.txt next to the word millionth.

**Connection**
ssh bandit7@bandit.labs.overthewire.org -p 2220
# Password: morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

**Solution**
bandit7@bandit:~$ ls
data.txt

bandit7@bandit:~$ cat data.txt | grep "millionth"
millionth	**dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc**
