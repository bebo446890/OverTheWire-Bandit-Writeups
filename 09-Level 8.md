# OverTheWire Bandit – Level 8 → Level 9

**Goal**
The password for the next level is stored in the file `data.txt` and is **the only line of text that occurs only once**.

**Connection**
ssh bandit8@bandit.labs.overthewire.org -p 2220
# Password: dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

**Solution**
bandit8@bandit:~$ sort data.txt | uniq -u
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
