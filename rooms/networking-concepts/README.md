# Networking Concepts — TryHackMe

**Room:** networking-concepts  
**Difficulty:** Beginner  
**OS:** Linux  
**Time to complete:** 15 minutes  
**Date completed:** 27-09-2025

## TL;DR
Opened two Linux virtual machines and practiced simple network service enumeration by connecting from one VM to the other using `telnet` on various ports. Interacted with an echo service (port 7), a daytime service (port 13), and an HTTP service (port 80) to observe responses and protocol information.

## Goal / Scope
- Practice basic network connectivity and service probing between two VMs.
- Learn how simple TCP services behave (echo, daytime, HTTP).
- Practice using `telnet` to connect to TCP services and inspect responses.

## Tools
- Two Linux virtual machines
- `telnet` client (from the attacking VM)

## Steps (what I did — command used)
1. Launched two Linux VMs and positioned one as the attacker and the other as the target.  
2. Connected to the target's echo service using `telnet 10.10.6.86 7` — typed text and observed it was echoed back by the server.  
3. Connected to the target's daytime service using `telnet 10.10.6.86 13` — received the server's current time-of-day response.  
4. Connected to the target's HTTP service using `telnet 10.10.6.86 80` — issued a simple HTTP request (for example `HEAD / HTTP/1.0`) to discover the HTTP version and server response headers.  
5. Observed and recorded the behavior and responses from each service to understand basic TCP service interactions.

## Lessons learned
- `telnet` is a quick way to connect to arbitrary TCP ports and manually interact with simple services.  
- The echo service (port 7) returns exactly what you send — useful for verifying raw TCP connectivity and round-trip text handling.  
- The daytime service (port 13) returns the server's current time — a simple informational service.  
- The HTTP service (port 80) provides protocol headers and version information when you send an HTTP request; manual requests show how HTTP responses and headers are structured.

## Notes
See `notes.md` for the minimal working log and `key-commands.md` for the exact commands used.
