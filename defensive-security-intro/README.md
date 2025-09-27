# Defensive Security Intro — TryHackMe

**Room:** defensive-security-intro  
**Difficulty:** Beginner  
**OS:** Web / Network lab  
**Time to complete:** 7 minutes  
**Date completed:** 24-09-2025

## TL;DR
Detected a suspicious IP in traffic using a SIEM tool, verified its reputation and location with a threat intelligence service, and blocked it using the firewall. Short exercise focused on basic defensive monitoring and incident response.

## Goal / Scope
- Practice basic traffic monitoring and threat detection.
- Identify potentially malicious IPs and respond appropriately.
- Document the incident in a safe lab environment.

## Tools
- SIEM tool
- Threat intelligence platform (e.g., Cisco Talos Intelligence)
- Firewall / network controls

## Steps (simple)
1. Open SIEM tool and scan through network traffic.
2. Identify any suspicious or unauthorized access attempts.
3. Note the IP address linked to the potential incident.
4. Perform a reputation and location check using a threat intelligence tool:
   - Verify whether the IP is known for malicious activity.
5. Confirm the IP is malicious.
6. Notify team lead / raise small incident report.
7. After receiving permission, block the IP using firewall controls.



## Lessons learned
- Regular traffic monitoring helps detect unauthorized access early.
- Reputation and geolocation checks can confirm threats quickly.
- Always escalate incidents appropriately before taking action.
- Firewalls provide a first line of defense against malicious IPs.

## Notes
See `notes.md` for the minimal working log





