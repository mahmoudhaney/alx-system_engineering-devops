# General
- Allowed editors: `vi`, `vim`, `emacs`
- All your scripts will be tested on Ubuntu 20.04 LTS
- All your scripts should be exactly two lines long (`$ wc -l file` should print 2)
- All your files should end with a new line (why?)
- The first line of all your files should be exactly `#!/bin/bash`
- A `README.md` file at the root of the repo, containing a description of the repository
- A `README.md` file, at the root of the folder of this project, describing what each script is doing
- You are not allowed to use backticks, `&&`, `||` or `;`
- All your scripts must be executable. To make your file executable, use the `chmod` command: `chmod u+x file`. Later, we’ll learn more about how to utilize this command.


# Practice Scenarios
- [x] [0-current_working_directory](0-current_working_directory) - Write a script that prints the absolute path name of the current working directory.

- [x] [1-listit](1-listit) - Display the contents list of your current directory.

- [x] [2-bring_me_home](2-bring_me_home) - Write a script that changes the working directory to the user’s home directory. You are not allowed to use any shell variables<br />

- [x] [3-listfiles](3-listfiles) - Display current directory contents in a long format

- [x] [4-listmorefiles](4-listmorefiles) - Display current directory contents, including hidden files (starting with `.`). Use the long format.

- [x] [5-listfilesdigitonly](5-listfilesdigitonly) - Display current directory contents. Long format with user and group IDs displayed numerically And hidden files (starting with .)

- [x] [6-firstdirectory](6-firstdirectory) - Create a script that creates a directory named `my_first_directory` in the `/tmp/` directory.

- [x] [7-movethatfile](7-movethatfile) - Move the file `betty` from `/tmp/` to `/tmp/my_first_directory`

- [x] [8-firstdelete](8-firstdelete) - Delete the file `betty`. The file betty is in `/tmp/my_first_directory`

- [x] [9-firstdirdeletion](9-firstdirdeletion) - Delete the directory `my_first_directory` that is in the `/tmp` directory.

- [x] [10-back](10-back) - Write a script that changes the working directory to the previous one.

- [x] [11-lists](11-lists) - Write a script that lists all files (even ones with names beginning with a period character, which are normally hidden) in the current directory and the parent of the working directory and the `/boot` directory (in this order), in long format.

- [x] [12-file_type](12-file_type) - Write a script that prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp` directory when we will run your script.

- [x] [13-symbolic_link](13-symbolic_link) - Create a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link should be created in the current working directory.

- [x] [14-copy_html](14-copy_html) - Create a script that copies all the HTML files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory. You can consider that all HTML files have the extension `.html`

- [x] [100-lets_move](100-lets_move) - Create a script that moves all files beginning with an uppercase letter to the directory `/tmp/u`. You can assume that the directory `/tmp/u` will exist when we will run your script

- [x] [101-clean_emacs](101-clean_emacs) - Create a script that deletes all files in the current working directory that end with the character `~`.

- [x] [102-tree](102-tree) - Create a script that creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory. You are only allowed to use two spaces in your script, not more.

- [x] [103-commas](103-commas) - Write a command that lists all the files and directories of the current directory, separated by commas (,).
  - Directory names should end with a slash (`/`) 
  - Files and directories starting with a dot (`.`) should be listed
  - The listing should be alpha ordered, except for the directories `.` and `..` which should be listed at the very beginning
  - Only digits and letters are used to sort; Digits should come first
  - You can assume that all the files we will test with will have at least one letter or one digit
  - The listing should end with a new line.

- [x] [school.mgc](school.mgc) - Create a magic file `school.mgc` that can be used with the command file to detect `School` data files. `School` data files always contain the string `SCHOOL` at offset 0 
