# Key commands used:

# Check which user is logged on
whoami

# Print a simple message to the terminal
echo hello

# List folders in the TryHackMe exercise directory
ls tryhackme/linux1/

# Change into a folder and list its contents (repeat for folder1..folder3)
cd tryhackme/linux1/folder1
ls

# Enter folder4 and list files
cd tryhackme/linux1/folder4
ls

# Display the contents of notes.txt
cat notes.txt

# Confirm current working directory
pwd

# (Learned about) Run a command in the background
# command &

# (Learned about) Chain commands so the next runs only if the previous succeeds
# command1 && command2

# Create/overwrite a file called 'passwords' with a password
echo password123 > passwords

# Append another line to the 'passwords' file
echo tryhackme >> passwords