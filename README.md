# Unix commands to help with projects - AM
### Listing files and directories
`ls` - list content of the current directory

`ls -a` - To list all files in directory including those whose names begin with a dot, type

`ls ~` - lists users home directory

`ls -1` - lists users home directory in column form

`ls -1a` - lists users home directory with hidden files in column form

`ls -t` - sorts home directories by time when used

`ls -S` - Sorts by size 

`ls *` - lists all subdirectories

`ls ~/..` - lists all users

### Changing to a different Directory
`cd` - change current working directory to home directory

`cd myDir` - change current working directory to 'myDir'

`cd /` - Change to root directory

`cd ~` - Also changes to home directory

`cd /home/user/Desktop` Change directory with absolute path

`cd .` - the current directory

### Pathnames
`pwd` - print working directory

### Create a file
`touch [filename]` - creates an empty file

### View file's content
`cat [filename]` - shows what is in the file

`head [filename]` - shows first ten lines of file

`tail [filename]` - show last ten lines of file

`less [filename]` - show file one line at a time

`cat >> [filename]` - add more items to file, (Control + D) to stop


### Text Output
`echo` - display text

### Output to the File
`echo (text) > [filename]` - sends text into file

### Remove Files and Directories
`rm [filename]` - remove file

`rm -rf (directoryname)` - remove directory

### Create Directory
`mkdir [directoryname]` - creates new directory

### Copying Files and Directories
`cp [filename] -/(destination)` - Copies file to a new destination

`cp [directoryname] -/(destination)` - Copies directory to a new destination

### Sort Files
`sort < [filename]` - sorts file in alphabetical order



