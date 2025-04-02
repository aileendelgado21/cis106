# Notes 5

## MKDIR

### Description 
* `mkdir` is used for creating a single directory or multiple directories. 
### Usage 
* `mkdir` + `option` + `name of directories`
### Examples 
* Create a directory in the current directory:
* `mkdir wallpapers`
* Create a directory in a different directory using relative path:
* `mkdir wallpapers/ocean`
* Create multiple directories:
* `mkdir wallpapers/cars wallpapers/cities wallpapers/forest`

## TOUCH

### Description 
* `touch` is used for creating files.
### Usage
* `touch` 
### Examples 
* To create a file called list:
* `touch list`
* To create several files:
* `touch list_of_cars.text script.py names.csv`
* To create a file using absolute path:
* `touch ~/Downloads/games.txt`
* To create a file with a space in its name:
* `touch "list of foods.txt`

## RM

### Description 
`rm` removes files.
### Usage
`rm` + `-r`+ `directory name or directory absolute path`
### Examples
* Remove a file: 
* `rm list`
* Remove a file and prompt confirmation before removal:
* `rm -i list`
* Remove all the files insides a directory and ask before removing more than 3 files:
* `rm -I Downloads/games/*` 

## RMDIR

### Description
`rmdir` removes empty directories.
### Usage 
`rmdir`
### Examples
* To remove an empty directory: 
* `rmdir Downloads/games`
* Removing multiple empty directories:
* `rmdir dir1 dir2 dir3`
  
## MV

### Description 
`mv` moves and renames directories. 
### Usage 
Basic Formula: ` mv` + `source` + `destination` 
For renaming files/directories the formula remains the same: `mv` + `file.directory to rename` + `new name`
### Examples 
BASIC FORMULA: 
* To move a file from a directory to another using relative path: 
* `mv Downloads/homework.pdf Documents/`
* To move a directory from one directory to another using absolute path:
* `sudo mv ~/Downloads/theme /usr/share/themes`
* To move a file from one directory to another combining absolute path and relative path:
* `mv Downloads/english_homework.docx /media/student/flashdrive/ `

RENAMING FILES/DIRECTORIES FORMULA:
* To rename a file:
* `mv homework.docx cis106homework.docx`
* To rename a file using absolute path:
* `mv ~/Downloads/homework.docx ~/Downloads/cis106homework.docx`

## CP
### Description 
`cp` copies files/directories from a source to a destination. 
### Usage 
`cp` + `files to copy` + `destination` 
* To copy directories you must use the `-r` options:
  `cp -r + directory to copy + destination`
### Examples
* To copy a file:
* `cp Downloads/wallpapers.zip Pictures/`
* To copy a directory with absolute path:
* `cp -r ~/Downloads/wallpapers ~/Pictures/ 
* To copy the content of a directory to another directory:
* `cp Downloads/wallpapers/* ~/Pictures/ 

## FILE

### Description 
`file` determines the file type of a file.
### Usage 
`file filename`
Display file type without file name:
`file -b filename`
### Examples 
* Create an empty file:
* `touch new-file.txt`
* Create multiple files:
* `touch notes.md program.py website.html`
* Create a file with a special character:
* `touch "Manuel Shopping List"`