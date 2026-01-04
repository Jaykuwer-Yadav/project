# project

hi this is Jay
git commands

1. git version
2. git config --global user.name"user.name"
3. git config --global user.email"jayyad71@gmail.com"
4. git config --list
5. git status
6. cd to go into github folder....
7. clear
8. ls (list to check files)
9. Get-ChildItem -Force (Too get hidden files )
    Basic all files: ls -Force or Get-ChildItem -Force shows everything including hidden/system files.
    Detailed view: ls -Force | Format-Table -AutoSize gives a table-like output similar to ls -la.
​   Long format: ls -Force | Select-Object Name, Length, LastWriteTime mimics ls -l with name, size, and date.
10. after that we see (M) 
git has 4 files 1. untracked 2.modified 3.staged 4.unmodified
2.modified files which u have modified 
For Untracked files:- means we made a new file in our folder apart from read.me
staged :- ready to commit
unmodified:- unchanged
![alt text](image-2.png)
11. git add <file name> eg. git add README.md
11(a). git add .(for adding all files in our directory)
12. git commit -m "some message" (holds record of change)

