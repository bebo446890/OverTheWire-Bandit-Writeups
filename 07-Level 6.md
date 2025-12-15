OverTheWire Bandit – Level 6 → Level 7

**Goal**
The password for the next level is stored somewhere on the server and has all of the following properties:

- Owned by user bandit7
- Owned by group bandit6
- 33 bytes in size

**Connection**
ssh bandit6@bandit.labs.overthewire.org -p 2220
# Password: HWasnPhtq9AVKe0dmk45nxy20cvUa6EG

**Solution**
bandit6@bandit:~$ find / -user bandit7 -group bandit6 -size 33c 2>/dev/null
/var/lib/dpkg/info/bandit7.password

bandit6@bandit:~$ cat /var/lib/dpkg/info/bandit7.password
**morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj**
