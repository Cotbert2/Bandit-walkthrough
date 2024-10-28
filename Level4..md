# Level 4-> Level 5

**Description:** The password for the next level is stored in the only human-readable file in the inhere directory. Tip: if your terminal is messed up, try the “reset” command.


## About Commands:
1. **cd:** cd Linux command is used to change the current working directory. It is a built-in command, which means that it is included directly into the shell. The cd command is available in all shells, including cmd, bash, and PowerShell.

2. **ls:** The ls command is used to list the files and directories in the current directory. By default, the ls command lists the names of all files and directories in the current directory. The ls command is one of the basic commands that any Linux user should know.

3. **file:** The file command is a standard program of Unix and Unix-like operating systems, which is used to determine the type of a file. The file command uses a series of tests to determine the file type.

4. **cat:** Cat command is used to concatenate and display the content of files. It can also be used to concatenate and display files. The cat command is mostly used for viewing the content of a file but it can also be used to create a new file, concatenate files, and redirect output in terminal.

**Notes**:
- In Linux files are able to do not have a extension, therefore you can call a file without extension.

- If you have a file with a tricki name is useful to write ***cd ./*** and then press the tab key to autocomplete the name of the file.

## Commands and common flags:

1. **cd** - Change Directory
    * **..** - Go to the parent directory
    * **/** - Go to the root directory
    * **~** - Go to the home directory
    * **-** - Go to the previous directory
    * "filename" - Go to the directory with the name "filename"

**command example:**

```bash
cd /path/to/directory
```

2. **ls** - List directory contents
    * **-l** - Use a long listing format
    * **-a** - Do not ignore entries starting with .


**command example:**

```bash
ls -la
```

3. **file** - Determine file type

**command example:**

```bash
file filename
```




4. **cat** - Concatenate files and print on the standard output

**command example:**

```bash
cat filename
```


## Theory:

In Linux everything is a file, even directories. The file command is used to determine the type of a file. The file command uses a series of tests to determine the file type. The file command is a standard program of Unix and Unix-like operating systems.


## Solution:

**Warning:** Just see the solutions if you are stuck. Try harder to solve the challenges; that's the best way to learn.

<details>
<summary>Solution:</summary>

1. Once you are in the bandit4 level, write the following command:

```bash
cd ./inhere
```

2. Now, list all files in the current directory:

```bash
ls -la
```

3. Now, use the file command to determine the type of each file:

```bash
file ./*
```
./* Operator ./* means all files in the current directory.
Also you can try each file one by one, but is more efficient to use the ./* operator.

The output for the file command will be something like this:

```bash
./-file00: data
./-file01: data
./-file02: data
./-file03: data
./-file04: data
./-file05: data
./-file06: data
./-file07: ASCII text
./-file08: data
./-file09: data
```

remember all in linux is a file, even data files or binary files, a readable human file could be ASCII text which means -file07 is the file we are looking for.

3. You now what to do, right? ;)

Of course, display the content of the file:

```bash
cat ./-file07
```

4. The password for the next level will be displayed.

***Password: 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw***

</details>

### See u in the level  ;)
