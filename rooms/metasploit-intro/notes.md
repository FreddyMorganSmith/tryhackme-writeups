# Notes — Metasploit Intro

## Quick log (27-minute session: 23:14 — 23:41)
- 23:14 — Opened Metasploit (`msfconsole`) and reviewed the console prompt and basic navigation.
- 23:16 — Discussed what Metasploit is used for (exploit development/execution, payload management, post-exploitation modules).
- 23:18 — Reviewed core concepts: exploit, vulnerability, payload.
- 23:19 — Talked through module categories: Auxiliary, Encoders, Evasion, Exploits, NOPs, payload types (Adapters, Singles, Stagers, Stages), post.
- 23:21 — Ran `search apache` to find Apache-related modules and note possible attack vectors.
- 23:23 — Ran `search auxiliary/scanner/ssh/ssh_login` to locate an SSH brute/credential scanner.
- 23:24 — Used `info` on the found module to view details (module metadata provided by `todb`).
- 23:25 — Executed `show options` to see required/optional module settings.
- 23:26 — Set RHOSTS for the current module: `set RHOSTS 10.10.174.56`.
- 23:28 — Learned about `setg` to apply settings globally; used `setg RHOSTS 10.10.19.23` as an example of a global setting.
- 23:30 — Set listener port with `set LPORT 6666`.
- 23:32 — Reviewed differences between `set` (module-local) and `setg` (global) and when to use each.
- 23:34 — Discussed payload types and how stagers/stages interact during exploitation.
- 23:36 — Practised the workflow: search → info → show options → set / setg → run (did not perform intrusive exploitation during this session).
- 23:38 — Summarised notes about modules and configuration practices; recorded key takeaways.
- 23:41 — Session complete.

## What I saw / thought
- Metasploit is best approached as a modular toolkit — use `search`/`info` to understand modules before configuring them.  
- `setg` is convenient for lab scenarios to avoid repeatedly setting the same option across modules, but be cautious using it in mixed-target environments.  
- Remember to check `show options` every time to ensure required values (RHOSTS, LPORT, etc.) are set appropriately.  
- The session reinforced the conceptual stack: vulnerability → exploit → payload → post-exploitation.
