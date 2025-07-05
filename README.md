## Level 0 - OverTheWire Bandit

**Objective**  
Log into the game server and retrieve the password for the next level.

**Details**  
- **Host:** bandit.labs.overthewire.org  
- **Port:** 2220  
- **Username:** bandit0  
- **Password:** ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If  

**Commands used**
```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
ls
cat readme
```

---

## Level 1 - OverTheWire Bandit

**Objective**  
Retrieve the password for Level 2 by reading the content of a file named `-`.

**Details**  
- **Host:** bandit.labs.overthewire.org  
- **Port:** 2220  
- **Username:** bandit1  
- **Password:** 263JGJPfgU6LtdEvgfWU1XP5yac29mFx  

**Commands used**
```bash
ssh bandit1@bandit.labs.overthewire.org -p 2220
ls
cat ./-
```
## Level 2 - OverTheWire Bandit

**Objective**  
Retrieve the password for Level 3 by reading the content of a file located in the `"spaces in this filename"` directory.

**Details**  
- **Host:** bandit.labs.overthewire.org  
- **Port:** 2220  
- **Username:** bandit2  
- **Password:** rWWA8WW33FYdLRjNuepIvAap6uZ9Y3M5  

**Commands used**
```bash
ssh bandit2@bandit.labs.overthewire.org -p 2220
ls
cd "spaces in this filename"
ls
cat file.txt

