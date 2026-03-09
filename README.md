# 🐧 Linux → Cloud Engineer Journal
**Thandolwami Mashele** | BCom Applied Information Systems, UJ

Documenting my journey from Linux foundations to AWS Certified Cloud Engineer.

---

## 🎯 Goal
AWS Certified Solutions Architect – Associate + Cloud Engineer role by early 2027.

## 📍 Current Phase
**Phase 1 — Linux Foundations (Week 1 Complete ✅ — Starting Document 2 Tomorrow)**

## 📅 Progress Log

| Date | What I Did | Status |
|------|-----------|--------|
| 3 Mar 2026 | Set up GitHub learning journal | ✅ Done |
| 3 Mar 2026 | Installed Git Bash on Windows | ✅ Done |
| 3 Mar 2026 | First terminal session — pwd, ls, cd, mkdir, touch, cat, echo, cp, mv, rm | ✅ Done |
| 3 Mar 2026 | Learned Linux file paths, flags, and permission strings | ✅ Done |
| 4 Mar 2026 | Lesson 1 — Navigation & file system structure | ✅ Done |
| 4 Mar 2026 | Lesson 2 — Creating, reading & editing files | ✅ Done |
| 4 Mar 2026 | Lesson 3 — Copy, move, delete | ✅ Done |
| 4 Mar 2026 | Exercise 1 — Navigate Like a Pro | ✅ Done |
| 4 Mar 2026 | Exercise 2 — Build study notes file | ✅ Done |
| 4 Mar 2026 | Exercise 3 — Cloud project folder structure | ✅ Done |
| 4 Mar 2026 | Exercise 4 — File operations drill | ✅ Done |
| 6 Mar 2026 | Exercise 5 — Backup simulation | ✅ Done |
| 6 Mar 2026 | Exercise 6 — Permissions practice | ✅ Done |
| 6 Mar 2026 | Exercise 7 — Search & grep | ✅ Done |
| 6 Mar 2026 | Exercise 8 — Pipe challenge | ✅ Done |
| 6 Mar 2026 | Exercise 9 — First scripts (hello, counter, files, info, greet) | ✅ Done |
| 9 Mar 2026 | Exercise 10 — Automated backup script | ✅ Done |
| 9 Mar 2026 | Boss Challenge — Built full study tracker from scratch | ✅ Done |

## 🏆 Boss Challenge — What I Built
A complete command-line study tracker including:
- Folder structure: `study-tracker/logs/notes/scripts/backups/`
- 6 lesson notes files covering all Week 1 topics
- `scripts.sh` — logs study sessions with date and topic to progress.log
- `backup-notes.sh` — automatically backs up notes to a dated folder
- Dated backup: `backups/2026-03-09/` created automatically with `$(date)`
- `grep` searches across all notes files
- Progress log with 2 study sessions recorded
  

## 📸 Boss Challenge Screenshots
![Study Tracker Structure](Screenshot__38_.png)
![Search Results & Progress Log](Screenshot__39_.png)


## 🧠 Key Things I Learned
- `pwd` = print working directory — always know where you are
- `~` = home, `..` = up one level, `.` = current folder
- `>` overwrites, `>>` appends — never mix these up
- `rm` has no recycle bin — gone forever
- Linux is case-sensitive — `Documents` ≠ `documents`
- Spaces in filenames need quotes — better to use hyphens
- `mkdir -p` creates nested folders in one command
- Always check `pwd` before cp, mv or rm
- You can't copy a folder into itself — go up one level first
- `grep -B/-A` shows context lines around matches
- Bash variables: no spaces around `=` ever
- `if` closes with `fi`, `for` closes with `done`
- `[ "$var" = "value" ]` needs spaces inside brackets
- `#!/bin/bash` must be the first line of every script
- `'single quotes'` = literal, `"double quotes"` = variables expanded
- `$(command)` captures command output into a variable
- `$(date +%Y-%m-%d)` creates dated folder names automatically
- `cat > file << 'EOF'` for writing multi-line scripts
- `$HOME` is safer than `~` when username has spaces
- `read -p "question" VARIABLE` gets input from user

## 📚 Commands Learned
`pwd` `ls` `ls -la` `cd` `cd ..` `cd ~` `cd -` `mkdir` `mkdir -p`
`touch` `echo` `cat` `head` `tail` `wc -l` `cp` `cp -r` `mv` `rm` `rm -i`
`chmod` `find` `grep` `grep -r` `grep -i` `grep -n` `grep -c` `grep -v`
`grep -B` `grep -A` `pipe |` `>` `>>` `wc` `sort` `date`

## 🛠 Scripts Written
- `hello.sh` — prints name, course and career goal
- `counter.sh` — counts from 1 to 10 with a for loop
- `files.sh` — loops through .txt files and prints each name
- `info.sh` — uses variables to print personal info in a sentence
- `greet.sh` — if/else checks name and prints personalised greeting
- `backup.sh` — copies cloudproject to dated backup folder
- `scripts.sh` — logs study sessions to progress.log
- `backup-notes.sh` — backs up notes to dated folder automatically

## 🛠 Environment
- OS: Windows 11 + Git Bash
- Editor: Visual Studio Code
- Cloud: AWS Free Tier

## 📜 Certifications Roadmap
- [ ] LPI Linux Essentials (Month 3)
- [ ] AWS Cloud Practitioner (Month 6)
- [ ] AWS Solutions Architect – Associate (Month 6)

## 🔗 Connect
[LinkedIn](https://linkedin.com/in/thandolwami-mashele)
