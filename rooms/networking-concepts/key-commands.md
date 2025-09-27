# Key commands used:

# Launch telnet to the echo service (echoes back text)
telnet 10.10.6.86 7

# Launch telnet to the daytime service (returns time of day)
telnet 10.10.6.86 13

# Launch telnet to the HTTP service (manual HTTP requests)
telnet 10.10.6.86 80

# Example manual HTTP request sent after connecting to port 80:
# Type this (then press Enter twice) to see headers / HTTP version:
HEAD / HTTP/1.0
# or
GET / HTTP/1.0

# (Optional) Quit telnet session
# Ctrl+] then type: quit
