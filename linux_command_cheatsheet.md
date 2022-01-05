### Not in alphabetical order!

| Command | Arguments | Description |
| :---         |     :---:      |          :--- |
| cd   |        | Change the directory |
| pwd     |       | Output of the current working path      |
| ls     |       | List a folder content      |
| ls     |   -l    | Long Listing    |
| ls     |   -a    | Displays everything even hidden files     |
| cat    |         | Shows the contents of a file or merges files |
| less    |         | Displays the contents of a file page by page (With additional functions like the search)  |
| more    |         | Displays the contents of a file page by page |
| stat    |         | Display file or file system status |
| hostnamectl    |         | Can be used to query and change the system's computer name and associated settings |
| date    |         | Displays the date and time |
| cal    |         | Displays the calendar |
| lsusb    |         | Displays the USB devices |
| lscpu    |         | Displays information about the CPU architecture |
| lspci    |         | Detailed information about the PCI devices and buses in the system |
| lsblk    |         | Lists information about all available or the specified block devices |
| df    |         |  Report file system disk space usage |
| df    |   -hT      |  Disk space allocation with (-h) "human readable" numbers and (-T) file system |
| uptime    |        |  Incl. CPU utilization 1min, 5min and 15min |
| uptime    |    -p    |  -p stands for "pretty" |
| uname    |        |  Displays the OS |
| uname    |    -a    |  -a for all info |
| touch    |        |  Update the access and modification times of each file to the current time. If the file does not exist, one will be created |
| rm    |        |  Remove files or directories |
| rm    |   -i *     |  * means delete all files, with -i prompt before every removal |
| rm    |    -f    | -f is for force, execute the command either way |
| rm    |    -r    |  Remove directories and their contents recursively |
| rm    |    -v    | -v is for verbose, explain what is being done |
| mkdir |          | Create the Directory(ies), if they do not already exist |
| rmdir |          | Remove empty (must be empty) directories => if not use rm -rf |
| cp    |          | Copy files and directories |
| cp    |    -R    | -r copy directories recursively |
| mv    |          | Move (or rename) files |
| ln    |          | Create symbolic and hard links |
| ln    |     -s   | Make symbolic links instead of hard links |
| echo  |          | Display a line of text |
| paste  |          | Merge lines of files |
| join  |          | Join lines of two files on a common field |
| expand  |          | Convert tabs to spaces |
| unexpand  |          | Convert spaces to tabs |
| sed  |          | Stream editor for filtering and transforming text (Syntax example: sed 's/this/through-this/g' file.txt) |
|      |          | s stands for substitute, g stands for global=all |
|  wc   |          | Print newline, word, and byte counts for each file |
|  wc   |    -l      | -l Print the newline counts (-l is an l stands for lines) |
|  chmod   |          | Change file mode bits |
|  chmod   |    ugo+x␣filename       | Set the execute bit for user, group and other for a file  |
|  chmod   |    755␣filename      | rwx the user, r-x for the group and r-x for others on a file  |
|  chgrp   |          | Change group ownership |
|  useradd   |          | create a new user or update default new user information |
|  useradd   |   -ms       | -m Create the user's home directory if it does not exist. -s The name of the user's login shell. |
