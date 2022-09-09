# The Command Line

The command line is a text-based interface; its appearance and behavior is defined by the shell being used, e.g. bash or zsh.

- `pwd` tells you where you are in the machine's file structure.

- `ls` shows what this location contains.

  - `-l` is an argument that gives more information about each item in the listing, e.g. permissions, owner, size, modification date
  
  - `[filepath]` can be added as an argument to show that location instead of the working directory.

  - a filename that starts with a `.` is hidden and will not display unless the argument `-a` is used.

- `cd <filepath>` changes your working directory

  - `~` is the root directory

  - `.` is the current directory

  - `..` is the parent directory

- `file <filepath>` tells you what type of file is located at the path (since everything is a file and the extensions don't matter)

  - filepaths can include spaces, but to get the terminal to correctly interpret the filename, it must be contained in quotes or have the space escaped with a `\`.

- `man <command>` brings up the manual page for the requested command.

  - `-k` allows a keywod search for a manual page instead.

  - `/<term>` allows you to search within a manual page.

- `mkdir <directory>` makes a new directory; the input name is really a filepath, so you can designate it to create the directory wherever instead of just in the current working directory.

  - `-p` creates parent directories as needed

- `rmdir <directory>` deletes an empty directory

- `rm <file>` deletes a file

  - `-r`, meaning recursive, can be used to delete a directory and everything inside it.

  - `-i` can be used in combination, giving a prompt before deleting each file.

- `touch` is used to modify access and modification times on a file. If it refers to a file that does not exist, it will create a blank file instead.

- `cp <source> <destination>` is used to copy a file to a new location; `-r` can be used here as well to copy a whole directory.

- `mv <source> <destination>` moves a file to a new location; `-r` is not required to move a directory.

  - it can also be used to rename a file by 'moving' it to the same directory
