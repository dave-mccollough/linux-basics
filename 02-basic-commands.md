# Basic Linux Commands

- Check current directory (present working directory)
  - `pwd`

- List directory contents
  - `ls`

- List directory contents with more details(long list)
  - `ls -l`

- List directory contents including hidden files
  - `ls -a`

- List directory contents in order created
  - `ls -lt`

- List directory contents in reverse order created
  - `ls -ltr`

- Create new directory
  - `mkdir <directory name>`
  - You can create multiple directories from the `mkdir` command
    - `mkdir <directory name> <directory name> <directory name>`
  - You can create nested directories with `mkdir` command
    - `mkdir <directory name>/<directory name>`
  
- Change directory
  - `cd <directory name>`
  
- Navigate up one directory
  - `cd ..`

- Navigate to the home directory from anywhere in the system
  - `cd`

- Navigate to a directory using the directory path
  - `cd /home/<directory name>`
  
- Move a file - This requires two arguments
- the first argument is the source location, the second argument is the destination location
  - `mv /home/<directory name>/<directory name> /home/<directory name>/<directory name>`

- Copy a file from one location to another location. This command expects two arguments
- the first argument is the source location, the second argument is the destination location
  - `cp /home/<directory name>/<directory name>/<file name> /home/<directory name>/<directory name>`

- Delete a file
  - `rm <directory name>/<directory name>/<file name>`

- View file contents
  - `cat <file name>`
  - `cat <directory name>/<directory name>/<file name>`
  
- Add contents to file
  - `cat > <file name>`
  - `cat > <directory name>/<directory name>/<file name>`
  - After command is issued, prompt will wait for user input

- Create a file
  - `touch <file name>`
  - `cat > <directory name>/<directory name>/<file name>`

***Pagers***

- Allow user to view file contents using `more` and `less` command
- `more <file name>`
  - [Space] scrolls data by screen
  - [Enter] scrolls date one line at a time
  - [b] scrolls data backwards
  - [/] search text

- `less <file name`
  - [Up arrow] scrolls up display one line at a time
  - [Down arrow] scrolls down display one line at a time
  - [/] search text

***Absolute and Relative paths***

- Absolute paths always start with the root directory and provide the full path to the file or directory
  - `cd /home/<directory name>/<directory name>`

- Relative path is a path to a file or directory that is relative to the current directory.
  - `cd <directory name>`