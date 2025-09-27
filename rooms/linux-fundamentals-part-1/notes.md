# Notes — Linux Fundamentals Part 1

## Quick log
- 17:04 — Opened terminal
- 17:06 — Ran: `whoami`
- 17:07 — Ran: `echo hello`
- 17:08 — Ran: `ls tryhackme/linux1/`
- 17:10 — Explored folders with `cd` and `ls`
- 17:13 — Found `notes.txt` in `folder4`
- 17:14 — Ran: `cd tryhackme/linux1/folder4` then `cat notes.txt`
- 17:16 — Confirmed location with `pwd`
- 17:17 — Reviewed `&` and `&&` (learned concept; no commands run)
- 17:18 — Ran: `echo password123 > passwords`
- 17:19 — Ran: `echo tryhackme >> passwords`
- 17:21 — Session complete

## What I saw / thought
- Directory tree contained four folders (folder1–folder4); only `folder4` had a file.
- `notes.txt` held a simple message — good practice for using `cat` and confirming context with `pwd`.
- Practiced file redirection: `>` to create/overwrite a file, `>>` to append.
- Reviewing `&` and `&&` clarified background execution vs conditional chaining — useful for later scripting.