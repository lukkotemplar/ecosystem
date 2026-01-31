# DOS COMMANDS
This is a list of DOS Commands. I will not include some commands that are obsolete or do not exist in version 6.22
## APPEND
Similar to PATH, it tells DOS where to search for program files.
## ATTRIB
Similar to chmod, it establishes attributes to files, with:
- A: Archive (Files are created with this attr. by default)
- S: System
- H: Hidden (Can't be listed with DIR)
- R: Read-only
To put an attribute to a file, ATTRIB [+|-][A|S|H|R] file
## CD
Same as cd. If no arguments are passed, it is similar to pwd
## CLS
Clears screen, same as clear
## FC
Compares 2 files and displays its contents
## COPY
Same as cp. To write text on console to a file, COPY CON file.txt. Type text, press CTRL + Z + Enter to finish
## DEL
Deletes files, same as rm.
## DELTREE
Deletes a directory along with all subdirectories and files, same as rm -rf
## DIR
Displays contents of directory, similar to ls
## XCOPY
Same as COPY, but can move also directories
## VOL
Displays disk volume label and serial number
## VER
Displays version of DOS
## UNDELETE
Restores files deleted with DEL
## TYPE
Similar to cat, displays content of files
## MORE
Used with TYPE to display more of the file
