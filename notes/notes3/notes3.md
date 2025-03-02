# Notes 3

## Echo
**Definition**: 
Display a line of text

**Usage**: 
`echo` + `option` + `string` 

**Example**: 
*  Display a line of text without the new line
   `echo -n "hello world"`
*  Display 2 lines of text that includes a horizontal tab 
   `echo -e "\hello world"`
* Display 2 lines of text in a single echo command
  `echo -e "line 1\nLine2"`

<hr>

## Date
**Definition**: Displays the current time and date.

**Usage**:
`data` + `option`

**Example**:
* Display current date
  `date` 
* Display current date in rfc 5322 format
  `date -R` 
  * Display the date and time from a specific time in the past
* `date -d "3 years ago"` 

<hr>

## Free
**Definition**: Displays the amount of free memory.

**Usage**:
`free` + `options` 

**Example**:
* Display memory utilization 
  `free` 
* Display memory utilization in human readable format 
  `free -h`
* Display a line containing the totals
  `free -t` 

<hr> 

## Uname
**Definition**: 
Print system information 

**Usage**:
`uname` + `option`

**Example**:
* Print all information 
  `uname -a`
* Print kernel information 
`uname -s`
* Print node names
  `uname -n` 

<hr>

## History
**Definition**: Displays the shell command history.

**Usage**:
`history` + `option`

**Example**:
* Display session history 
  `history`
* Clear session history 
  `history`
* Re-executing the last command
  `!!`

<hr>

## Man
**Definition**:Man (manual) pages are documentation files that describe Linux shell commands, executable programs, systems calls, special files, and so forth.

**Usage**: 
`man` + `option` + `command` 

**Example**:
* Open the man page of echo command
  `man echo`
* Open a specific man page 
  `man 5 passwd`
* Show all available man pages
  `man -f passwd`

<hr>

## Apt
**Definition**:
A set of tools for managing debian packages

**Usage**:
`sudo` (if required) + `apt` + `apt action` +`package`

**Example**:
* Update and upgrade 
  `sudo apt update & sudo apt upgrade -y`
* Install a program 
  `sudo apt install firefox`
* Remove a program
  `sudo apt remove firefox` 

<hr>

## Snap
**Definition**:
Snaps are app packages for desktop, cloud and IoT that are easy to install, cross platform and dependency free 
**Usage**:
`sudo` (if needed) + `snap` + `action` + `package name`

**Examples**:
* Find a snap
  `snap search "video player"`
* Install a snap
  `sudo snap install vlc"`
* Remove a snap
  `sudo snap remove vlc"`

<hr>

## Flatpak 
**Definition**:
Flatpak is a next generation technology for packaging, distributing, and managing software in Linux

**Usage**:
`sudo` (if needed) + `flatpak` + `action` + `package id`

**Example**:
* Search for package 
  `flatpak search "video player"
* Install flatpak
  `flatpak install org.videolan.VLC`
* Remove flatpak
  `flatpak remove org.videolan.VLC`

