# TryHackMe Writeups

## Offensive Security Intro
**Difficulty:** Beginner  
**Time to Complete:** 7 minutes  
**Summary:** Found a hidden web directory using `dirb` and inspected it in the browser. Basic web enumeration practice.  
**Writeup:** [README](offensive-security-intro/README.md)

## Defensive Security Intro
**Difficulty:** Beginner  
**Time to Complete:** 7 minutes  
**Summary:** Detected a suspicious IP in traffic using a SIEM tool, verified its reputation and location with a threat intelligence service, and blocked it using the firewall. Short exercise focused on basic defensive monitoring and incident response. 
**Writeup:** [README](defensive-security-intro/README.md)

## Linux Fundamentals Part 1
**Difficulty:** Beginner  
**Time to Complete:** 17 minutes  
**Summary:** Practiced basic Linux shell commands (`whoami`, `ls`, `cd`, `cat`, `pwd`, `echo`) while exploring `tryhackme/linux1/`. Found `notes.txt` in `folder4`, read its contents, and practiced file redirection (`>`, `>>`). Good intro to filesystem navigation and command redirection.  
**Writeup:** [README](linux-fundamentals-part-1/README.md)

## Networking Concepts
**Difficulty:** Beginner  
**Time to Complete:** 15 minutes  
**Summary:** Opened two Linux VMs and practised basic network service enumeration using `telnet` to connect to services on 10.10.6.86 (port 7 echo, port 13 daytime, port 80 HTTP). Observed echo responses, time strings, and HTTP headers to learn basic TCP service behavior.  
**Writeup:** [README](networking-concepts/README.md)

## Cryptography Basics
**Difficulty:** Beginner  
**Time to Complete:** 10 minutes  
**Summary:** Introductory concepts: plaintext vs ciphertext, encryption/decryption, ciphers and keys. Practised Caesar cipher decryption (XRPCTCRGNEI → ICANENCRYPT) and reviewed XOR logic and modulo examples. No tools or VMs required.  
**Writeup:** [README](cryptography-basics/README.md)

## Metasploit Intro
**Difficulty:** Beginner  
**Time to Complete:** 27 minutes  
**Summary:** Intro to Metasploit and `msfconsole`: learned module types (Auxiliary, Exploits, Encoders, payloads, post), practised searching modules (`search apache`, `search auxiliary/scanner/ssh/ssh_login`), inspected modules with `info` (module provided by `todb`), used `show options`, configured `RHOSTS`, `LPORT`, and used `setg` for global settings.  
**Writeup:** [README](Metasploit-intro/README.md)

