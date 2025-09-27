# Notes — Networking Concepts

## Quick log
- 21:59 — Opened both Linux virtual machines and prepared attacker/target roles
- 22:00 — Verified network connectivity between VMs (ping/basic checks)
- 22:01 — Connected to echo service: `telnet 10.10.6.86 7`
- 22:02 — Typed text into echo session and observed it being echoed back
- 22:03 — Closed echo session
- 22:04 — Connected to daytime service: `telnet 10.10.6.86 13`
- 22:05 — Observed the server's time-of-day response from the daytime service
- 22:06 — Closed daytime session
- 22:07 — Connected to HTTP service: `telnet 10.10.6.86 80`
- 22:08 — Sent `HEAD / HTTP/1.0` (press Enter twice) to inspect response headers and HTTP version
- 22:09 — Noted server/HTTP version and common response headers
- 22:10 — Tried `GET / HTTP/1.0` to see full response body (if present)
- 22:11 — Closed HTTP telnet session and recorded findings
- 22:12 — Summarised observed service behaviours
- 22:13 — Wrote down key differences between services
- 22:14 — Session complete

## What I saw / thought
- Echo service (port 7) simply sent back exactly what was typed — good for verifying raw TCP connectivity and round-trip text handling.  
- Daytime service (port 13) returned a timestamp string — useful for quick informational checks.  
- HTTP service (port 80) returned protocol headers and body when queried manually; `HEAD` was useful to quickly discover HTTP version and headers without downloading a full body.  
- `telnet` is a quick, manual tool to interact with arbitrary TCP services for basic enumeration and learning.
