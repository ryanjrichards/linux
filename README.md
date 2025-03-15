# Linux Commands Reference

This repository contains a list of commonly used Linux commands along with their descriptions. The commands are categorized for easy reference.

## Categories

- **Superuser**
  - `sudo`: superuser do

- **Package Managers**
  - `dnf`: package manager for RHEL
  - `apt`: package manager for Ubuntu/Debian

- **Manual**
  - `man`: manual

- **Navigation**
  - `cd`: change directory
  - `ls`: list files

- **File Operations**
  - `cp`: copy
  - `rm`: remove
  - `mv`: move

- **Directory Operations**
  - `mkdir`: make directory
  - `rmdir`: remove directory

- **File Creation**
  - `touch`: create file

- **File Viewing**
  - `cat`: concatenate
  - `more`: read file
  - `less`: read file

- **Linking**
  - `ln`: hard link - must be on same volume
  - `ln -s`: soft link - can be anywhere but relies on the path
  - `rsync`: backup

- **Text Editors**
  - `nano`: simple text editor
  - `vim`: more advanced

  ### Vim Commands
  - `i`: insert
  - `esc`: leave insert mode
  - `:`: enter command in command mode
  - `:w`: write to disk
  - `:q`: quit
  - `:wq`: write and quit
  - `d`: delete
  - `dd`: delete line
  - `:1,10d`: delete lines 1-10
  - `:1000`: go to line 1000
  - `:/text`: search for text
  - `:%s/text/replacement`: replace text with replacement
  - `hjkl`: move cursor
  - `yy`: copy line
  - `p`: paste line
  - `:q!`: quit without saving
  - `:w filename.txt`: write to filename.txt

- **File Search**
  - `find`: find files
  - `find / -name filename.txt`: search for filename.txt starting at root
  - `find / -name "*.txt"`: search for all txt files starting at root
  - `find / -name "*.txt" 2>/dev/null`: suppress error messages
  - `find / -user username`: search for files owned by username
  - `find / -size +100M`: search for files larger than 100M

- **Database Search**
  - `locate`: find files using a database
  - `sudo updatedb`: update the database
  - `locate filename.txt`: search for filename.txt

- **Command Information**
  - `type`: find out what a command does
  - `type ls`: find out what ls does

- **Command Location**
  - `which`: find out where a command is located
  - `which ls`: find out where ls is located

## Usage

Refer to the `commands` file for a comprehensive list of commands and their descriptions.
