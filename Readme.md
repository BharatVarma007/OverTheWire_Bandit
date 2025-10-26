# Bandit — OverTheWire (Levels 0 → 15)

This README collects the commands and passwords you provided for the **OverTheWire Bandit** wargame from level 0 up to level 15. Use it as a reference while playing or studying the challenges.

> **Note:** These are user-supplied entries. Treat passwords as sensitive and do not share them publicly.

---

## Table of contents

- Level 0 → 1
- Level 1 → 2
- Level 2 → 3
- Level 3 → 4
- Level 4 → 5
- Level 5 → 6
- Level 6 → 7
- Level 7 → 8
- Level 8 → 9
- Level 9 → 10
- Level 10 → 11
- Level 11 → 12
- Level 12 → 13
- Level 13 → 14
- Level 14 → 15
- Level 15 → 16

---

### Level 0 → 1

**Commands:**

```bash
ls -als
cat readme
```


### Level 1 → 2

**Password:**

```
ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If
```

**Commands:**

```bash
ls -als
cat ./-
```

*(Found password listed in the file `-`)*

---

### Level 2 → 3

**Password:**

```
MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
```

**Commands:**

```bash
ls -alps
cat -- "--spaces in this filename--"
```

---

### Level 3 → 4

**Password:**

```
2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ
```

**Commands:**

```bash
ls -als
cd ./inhere
ls -als
cat ...Hiding-From-You
```

---

### Level 4 → 5

**Password:**

```
4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
```

**Commands:**

```bash
ls -als
cd ./inhere
ls -als
find . -type f | xargs file
cat ./-file07
```

---

### Level 5 → 6

**Password:**

```
HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
```

**Commands:**

```bash
ls
cd ./inhere
find . -type f -size 1033c ! -executable
cat ./maybehere07/.file2
```

---

### Level 6 → 7

**Password:**

```
morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
```

**Commands:**

```bash
find / -type f -user bandit7 -group bandit6 -size 33c
cat /var/lib/dpkg/info/bandit7.password
```

---

### Level 7 → 8

**Password:**

```
dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
```

**Commands:**

```bash
ls
strings data.txt | grep "millionth"
```

---

### Level 8 → 9

**Password:**

```
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
```

**Commands:**

```bash
sort data.txt | uniq -c
```

---

### Level 9 → 10

**Password:**

```
4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
```

**Commands:**

```bash
strings data.txt | grep "="
```

---

### Level 10 → 11

**Password:**

```
dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
```

**Commands:**

```bash
cat data.txt
base64 -d data.txt
```

---

### Level 11 → 12

**Password:**

```
7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
```

**Commands:**

```bash
cat data.txt
```

*Then apply ROT13 (e.g. using CyberChef or `tr 'A-Za-z' 'N-ZA-Mn-za-m'`).*

---

### Level 12 → 13

**Password:**

```
FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
```

---

### Level 13 → 14

**Password:**

```
MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
```

---

### Level 14 → 15

**Password:**

```
8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
```

**Commands:**

```bash
cat /etc/bandit_pass/bandit14
nc localhost 30000
```

---

### Level 15 → 16

**Password:**

```
kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
```

**Commands:**

```bash
cat /etc/bandit_pass/bandit15
ncat --ssl localhost 30001
```

---

## License / Disclaimer

This document is for personal study/reference. Do not distribute passwords or use them on systems you do not own or have permission to access.

---

*End of README*

