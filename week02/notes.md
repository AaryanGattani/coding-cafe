# Coding Cafe Assignment : (Lab01)
## Aaryan Gattani

1. It showed me my the absolute path to my current location
2. It revealed all hidden files and folders.
3. The first column (which looks like -rw-r--r-- or drwxr-xr-x) indicates the file type and its permissions.
4. It works because we are going back to the parent directory and then moving into the sub directory,It is a relative path as it does not include the entire users,folder/folder/folder...
5. It moved a file, and renamed it.
6. 12 Folders
7. /opt/anaconda3/bin/python3
8. No they aren't same as the person beside me is using WSL, while I am on MacOS.
9. The shell said pyton3: command not found. This means the shell checked every directory listed in my PATH from left to right, but could not find any program named pyton3 inside any of them.
10. Because the folder name starts with a dot (.), making it a hidden directory. Plain ls ignores hidden items.
11. The terminal prompt was updated to include (.venv) at the beginning.
12. No, it is not the same path. It changed from Anaconda Python to .venv/bin/python3. This tells that running activate added the virtual environment's bin folder to the very front of your PATH, forcing your shell to use the isolated Python inside the .venv folder.
13. requests, and supporitng packages like certifi,charset-normalizer, idna, urllib3  
14. It points back to system's default Python installation because running deactivate removed the virtual environment from your PATH.
15. l -h displays file sizes in an easy-to-read format (like kilobytes 'K', megabytes 'M', or gigabytes 'G') rather than raw bytes.
16. Ctrl + C cancelled the current command you were typing (showing a KeyboardInterrupt) but kept the Python prompt open. Ctrl + D made it exit and return to the normal terminal prompt.