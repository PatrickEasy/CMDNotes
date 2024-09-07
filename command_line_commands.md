
# Common Command-Line Commands

## File and Directory Management
1. **`ls`** - Lists files and directories in the current directory.
   - Example: `ls -la` (lists all files with details, including hidden files)

2. **`cd`** - Changes the directory.
   - Example: `cd Documents/` (moves to the "Documents" directory)

3. **`pwd`** - Prints the current working directory.
   - Example: `pwd` (shows the full path of your current location)

4. **`mkdir`** - Creates a new directory.
   - Example: `mkdir new_folder` (creates a directory named "new_folder")

5. **`rm`** - Removes files or directories.
   - Example: 
     - `rm file.txt` (removes a file)
     - `rm -r folder/` (removes a folder and its contents recursively)

6. **`cp`** - Copies files or directories.
   - Example: `cp file.txt backup.txt` (copies "file.txt" to "backup.txt")

7. **`mv`** - Moves or renames files or directories.
   - Example: `mv file.txt new_folder/` (moves "file.txt" into "new_folder")

## Viewing and Editing Files
8. **`cat`** - Displays the contents of a file.
   - Example: `cat file.txt` (prints the contents of "file.txt" to the screen)

9. **`nano`** or **`vim`** - Text editors in the terminal.
   - Example: `nano file.txt` (opens "file.txt" for editing)

10. **`head`** and **`tail`** - Shows the beginning or end of a file.
    - Example: `head -n 5 file.txt` (shows the first 5 lines of "file.txt")
    - Example: `tail -n 10 file.txt` (shows the last 10 lines of "file.txt")

## File Permissions and Ownership
11. **`chmod`** - Changes file permissions.
    - Example: `chmod 755 script.sh` (makes "script.sh" executable)

12. **`chown`** - Changes file ownership.
    - Example: `sudo chown user:group file.txt` (changes ownership of "file.txt" to "user" and group to "group")

## System Information
13. **`df`** - Shows disk space usage.
    - Example: `df -h` (shows disk usage in a human-readable format)

14. **`du`** - Shows the size of files or directories.
    - Example: `du -sh folder/` (shows the size of "folder")

15. **`top`** - Displays running processes and system resource usage.
    - Example: `top` (interactive, live system monitor)

16. **`ps`** - Lists running processes.
    - Example: `ps aux` (shows detailed info on all running processes)

## Network
17. **`ping`** - Sends ICMP echo requests to test network connectivity.
    - Example: `ping google.com` (tests connection to Google)

18. **`ifconfig`** or **`ip`** - Displays network interface information.
    - Example: `ifconfig` (shows network details like IP addresses)

19. **`curl`** - Transfers data from or to a server.
    - Example: `curl https://example.com` (downloads a webpage's content)

## Other Useful Commands
20. **`grep`** - Searches for patterns in files.
    - Example: `grep "error" log.txt` (searches for the word "error" in "log.txt")

21. **`find`** - Searches for files or directories.
    - Example: `find . -name "*.txt"` (finds all `.txt` files in the current directory and subdirectories)

22. **`history`** - Shows the command history.
    - Example: `history` (displays a list of previously executed commands)

23. **`man`** - Shows the manual or help page for a command.
    - Example: `man ls` (shows the manual for the `ls` command)
