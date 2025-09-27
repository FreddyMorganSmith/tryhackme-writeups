# Cryptography Basics — TryHackMe

**Room:** cryptography-basics  
**Difficulty:** Beginner  
**OS:** N/A  
**Time to complete:** 10 minutes  
**Date completed:** 27-09-2025

## TL;DR
Learned core cryptography concepts without needing tools or VMs: plaintext vs ciphertext, encryption and decryption, ciphers and keys. Practiced a Caesar cipher decryption (XRPCTCRGNEI → ICANENCRYPT) and reviewed XOR logic and modulo examples.

## Goal / Scope
- Understand basic cryptography concepts.
- Learn the difference between plaintext and ciphertext.
- See how encryption and decryption work at a high level.
- Practice simple ciphers (Caesar) and basic binary/arithmetics used in crypto (XOR, modulo).

## Tools
- None (the exercise is conceptual / interactive — no tools or VMs required)

## Steps (what I did — action/result)
1. Asked questions about common encryption standards and their purposes.  
2. Learned the difference between plaintext (readable data) and ciphertext (encrypted data).  
3. Covered what encryption (transforming plaintext into ciphertext) and decryption (reversing that process) mean.  
4. Discussed ciphers and keys — how a cipher is the algorithm and a key parameterises it.  
5. Practised a Caesar cipher decryption: `XRPCTCRGNEI` → `ICANENCRYPT`.  
6. Reviewed XOR logic and modulo arithmetic with example results:
   - `1001 XOR 1010 = 0011`  
   - `118613842 % 9091 = 3565`  
   - `60 % 12 = 0`  
7. No shell/CLI commands were required for this room.

## Lessons learned
- Cryptography separates data (plaintext) from secure representations (ciphertext) using algorithms and keys.  
- Simple classical ciphers (like Caesar) are useful to understand substitution encryption basics.  
- XOR and modulo operations are fundamental building blocks in many cryptographic algorithms and protocols.  
- Understanding the difference between algorithm (cipher) and secret (key) is essential.

## Notes
See `notes.md` for the minimal working log
