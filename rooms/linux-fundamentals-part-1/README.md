# Linux Fundamentals Part 1 — TryHackMe

**Room:** linux-fundamentals-part-1
**Difficulty:** Beginner  
**OS:** Linux
**Time to complete:** 17 minutes  
**Date completed:** 27-09-2025

## TL;DR
Practiced basic Linux shell commands: checked the current user, explored directories in `tryhackme/linux1/`, viewed a note in `folder4`, and practiced file redirection. Learned about `&` and `&&` operators.

## Goal / Scope
- Practice Linux terminal commands and filesystem navigation.
- Explore folders and read files.
- Learn basic file redirection.

## Tools
- Linux terminal (bash)

## Steps (what I did — command used)
1. Checked which user is logged on — `whoami`  
2. Displayed a simple message in the terminal — `echo hello`  
3. Listed folders in the TryHackMe exercise directory to see what was there — `ls tryhackme/linux1/`  
   - Output: `folder1  folder2  folder3  folder4`  
4. Explored each folder to inspect contents — `cd tryhackme/linux1/folder1` / `ls`, repeat for folder2 and folder3 (no relevant files)  
5. Entered `folder4` and listed its contents — `cd tryhackme/linux1/folder4` / `ls`  
6. Read the note inside `folder4` — `cat notes.txt`  
7. Confirmed current working directory for context — `pwd`  
8. Reviewed what `&` (background execution) and `&&` (conditional chaining) do — (learned concept; no command executed)  
9. Practised file redirection by creating and appending to a `passwords` file — `echo password123 > passwords` then `echo tryhackme >> passwords`

## Lessons learned
- Core shell commands (`whoami`, `pwd`, `ls`, `cd`, `cat`, `echo`) are essential for navigating and inspecting a Linux filesystem.  
- `>` overwrites or creates files; `>>` appends to files.  
- `&` runs a command in the background; `&&` runs the next command only if the previous one succeeds.

## Notes
See `notes.md` for the minimal working log and `key-commands.md` for the exact commands used.