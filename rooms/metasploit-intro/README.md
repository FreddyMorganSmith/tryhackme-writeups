# Metasploit Intro — TryHackMe

**Room:** Metasploit-intro  
**Difficulty:** Beginner  
**OS:** Linux  
**Time to complete:** 27 minutes  
**Date completed:** 27-09-2025

## TL;DR
Introduction to Metasploit and the `msfconsole` interface. Reviewed core concepts (exploit, vulnerability, payload), learned about module types (Auxiliary, Encoders, Evasion, Exploits, NOPs, payload types, post), and practised using search, info, show options, set / setg, and configuring listeners/targets.

## Goal / Scope
- Learn what Metasploit is used for and how `msfconsole` works.  
- Review exploit/payload concepts and module categories.  
- Practice basic module discovery and configuration commands.

## Tools
- Metasploit Framework (`msfconsole`)

## Steps (what I did — command used)
1. Opened Metasploit console — `msfconsole`  
2. Briefly reviewed what Metasploit is used for (framework for developing/executing exploits, managing payloads, post-exploitation).  
3. Practised searching for modules: `search apache` to find Apache-related modules.  
4. Searched a specific auxiliary scanner module: `search auxiliary/scanner/ssh/ssh_login` then inspected module details with `info` (module provided by `todb` in this case).  
5. Checked module options with `show options`.  
6. Set target host(s): `set RHOSTS 10.10.174.56`  
7. Learned the global setter shorthand and effect: `setg` = set global (applies to all modules).  
8. Set local listener port: `set LPORT 6666`  
9. Set a global RHOSTS value: `setg RHOSTS 10.10.19.23`  
10. Reviewed payload types and module categories (Auxiliary, Encoders, Evasion, Exploits, NOPs, payload: Adapters/Singles/Stagers/Stages, post) and how they fit into an attack workflow.

## Lessons learned
- `msfconsole` is a powerful interactive environment for discovering and configuring modules, not just running exploits.  
- `search` and `info` are essential for finding and understanding modules; `show options` reveals required configuration.  
- `set` configures a module-specific option; `setg` configures a global option that persists across modules.  
- Understanding module types and payload architectures (singles, stagers, stages) is critical for selecting the right workflow and avoiding common mistakes.

## Notes
See `notes.md` for a concise session log and `key-commands.md` for exact commands used.
