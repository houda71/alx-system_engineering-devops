# 0x00-shell_basics
## A short description for each file:
* `0-current_working_directory` contain a script to print the current working directory.
* `1-listit contain` script to list files and directorys in inthe current working directory.
* `2-bring_me_home` contain script to changes the working directory to the user’s home directory.
* `3-listfiles` contain script to display current directory contents in a long format.
* `4-listmorefiles` contain script to display current directory contents, including hidden files. Useing the long format.
* `5-listfilesdigitonly` contain script to display current directory contents:
  * Long format.
  * with user and group IDs displayed numerically.
  * And hidden files.
* `6-firstdirectory` contain a script that creates a directory named `my_first_directory` in the `/tmp/` directoiry.
* `7-movethatfile` contain a script to move the file `betty` from `/tmp/` to `/tmp/my_first_directory`.
* `8-firstdelete` contain a script to delete the file `betty` in the path `/tmp/my_first_directory`.
* `9-firstdirdeletion` contain a script to delete the directory `my_first_directory` that is in the `/tmp` directory.
* `10-back` contain a script to changes the working directory to the previous one.
* `11-lists` contain a script to lists all files (even hidden) in the current directory and the parent of the working directory and the `/boot` directory, in order and long format.
* `12-file_type` contain script to prints the type of the file named `iamafile`. The file `iamafile` will be in the `/tmp` directory.
* `13-symbolic_link` contain script to create a symbolic link to `/bin/ls`, named `__ls__`. The symbolic link will created in the current working directory.
* `14-copy_html` contain script to copies all the `HTML` files from the current working directory to the parent of the working directory, but only copy files that did not exist in the parent of the working directory or were newer than the versions in the parent of the working directory.
* `100-lets_move` contain script to moves all files beginning with an uppercase letter to the directory `/tmp/u`.
* `101-clean_emacs` contain script to  deletes all files in the current working directory that end with the character `~`.
* `102-tree` contain script to  creates the directories `welcome/`, `welcome/to/` and `welcome/to/school` in the current directory.
* `103-commas` contain script to lists all the files and directories of the current directory, separated by commas (,).

  * Directory names should end with a slash (`/`).
  * Files and directories starting with a dot (`.`) should be listed.
  * The listing should be alpha ordered, except for the directories `.` and `..` which should be listed at the very beginning.
  * Only digits and letters are used to sort; Digits should come first.
  * You can assume that all the files we will test with will have at least one letter or one digit.
  * The listing should end with a new line.
* `school.mgc` : This magic file contain a rules that can be used with the command `file` to detect `School` data files that contain the string `SCHOOL` at offset 0.
