# Introduction to the Linux Shell

- The Linux shell is a command line interface (CLI)
- The initial directory in Linux shell is the home directory `/home`
- Users are created under the `/home` directory - `/home/dave`
- A users home directory name is the same as the name of the user and is unique to that user
- Users can store files, directories, etc in their home directory
- The home directory is represented by the tilde `~`
- Command line prompts can be configured to show whatever the user wants
- Linux has two different types of commands
  - Internal Commands
    - Built-in commands
      - `echo`, `cd`, `pwd`, etc..
  - External Commands
    - Scripts that are preinstalled with the Linux distribution
      - `mv`, `date`, `uptime`, `cp`, etc..
  - To determine if a command is internal or external, use the `type` command
    - `type echo`
