1. The 'pwd' command prints the path to the position that you are currently in.
2. ls -a prints the '.' and '..' entries alongside the files which shows the current directory and the parent directory respectively while ls does not. Additionally, ls -a shows the hidden files, if any, while ls does not. 
3. ls-l: 
drwxrwxrwx 1 root root 4096 Aug 27 13:16  coding-cafe
The first column of the ls -l output shows the access permissions
4. It works from the home position because it provides a directory to be read within the current position (as coding-cafe/week02 is directly inside of my home directory). It is a relative path as it gives the path to the position from my current position rather than the entire path leading to that position. 
5. In the first occurance of the 'mv' command, it moved the copied README-backup.md file into week01/
Then, in the second occurance, it renamed README-backup.md into old-readme.md.
6. There are 20 files
7. /usr/bin/python3
8. They are the same
9. "Command 'pyton3' not found, did you mean:
  command 'python3' from deb python3 (3.14.3-0ubuntu2)
Try: sudo apt install <deb name>"
The shell said that there is no such path with 'pyton3' and in turn recommended a path that exists ('python3')
10. This is because .venv is a hidden file and only ls -a displays hidden files.
11. It displays (.venv) at the beginning of the prompt which shows the python environment in which it is.
12. /home/trisha/coding-cafe/.venv/bin/python3
This shows that the command succesfully isolated the path in the specific environment directory.
13. pip list 1:
pip     25.1.1
pip list 2: 
certifi            2026.7.22
charset-normalizer 3.5.1
idna               3.19
pip                25.1.1
requests           2.34.2
urllib3            2.7.0
14. /usr/bin/python3
15. According to the manual for ls, ls -h makes it readable for humans
16. Ctrl + C makes a keyboard interruption. Meanwhile, Ctrl + D makes the computer exit the interpreter and return to previous file path.
