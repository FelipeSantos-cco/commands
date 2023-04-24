# Commands
## Creating commands for the linux terminal

### How to create a command?
1° Create a name that doesn't interfere with existing commands;

2° Create a file with that name and no extension in a folder that is in the path, for example: `/usr/local/bin`.
> ```bash
> sudo touch /usr/local/bin/command-name
> ```

3° Open the file with a text editor and add the command you want to run;
> ```bash
> #!/bin/bash
> echo "My command HEEEEE !!!!!!"
> ```

4° Save the file;

5° Give execute permission to the file:
> ```bash
> sudo chmod +x /usr/local/bin/command-name
> ```

6° Now you can run the command from anywhere in the terminal :smile:

---

### List of Commands
| name | description | it's at |
| :--: | :---------: | :-----: |
| pull-all | Run git pull command on all repositories. | [pull-all](./pull-all) |
