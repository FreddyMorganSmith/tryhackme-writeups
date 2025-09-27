# Key commands used:

# Start Metasploit console
msfconsole

# Search for Apache-related modules
search apache

# Search for specific auxiliary SSH login scanner
search auxiliary/scanner/ssh/ssh_login

# Show detailed information about a module (run after selecting or specifying a module)
info

# Show configurable options for the currently selected module
show options

# Set target host(s) for the current module
set RHOSTS 10.10.174.56

# Set an option globally (applies to all modules)
setg RHOSTS 10.10.19.23

# Set local listener port
set LPORT 6666

# Example: set an option only for the current module (alternative)
set TARGET 1

# Quit msfconsole
exit
