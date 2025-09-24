# Offensive Security Intro — TryHackMe

**Room:** offensive-security-intro
**Difficulty:** Beginner  
**OS:** Web-based lab  
**Time to complete:** 7 minutes  
**Date completed:** 24-09-2025

## TL;DR
Found a hidden web directory on `fakebank.thm` using `dirb` and inspected the discovered page in a browser. Short exercise focused on basic web enumeration.

## Goal / Scope
- Practice basic web enumeration.
- Discover hidden directories and manually inspect results in a browser.

## Tools
- `dirb` 
- Web browser

## Steps (simple)
1. Run a directory scan with `dirb`:
 - dirb http://fakebank.thm
2. From the `dirb` output, copy a discovered hidden path (example: `/hiddenpanel`) and paste it into your browser:
 - http://fakebank.thm/hiddenpanel
3. Inspect the page in the browser for further clues or functionality. (No further exploitation performed)

## Lessons learned
- `dirb` is a fast way to find directories on web targets.
- Always follow up automated findings with manual inspection in a browser.

## Notes
See `notes.md` for the minimal working log and `key-commands.md` for the exact command used.



