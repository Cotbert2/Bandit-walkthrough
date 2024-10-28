# Level 3-> Level 4

**Description:** The password for the next level is stored in a hidden file in the inhere directory.


## About Commands:
1. **cat:** Cat command is used to concatenate and display the content of files. It can also be used to concatenate and display files. The cat command is mostly used for viewing the content of a file but it can also be used to create a new file, concatenate files, and redirect output in terminal. 
In simple words, the cat command is used to display the content of a file.

2. **ls:** The ls command is used to list the files and directories in the current directory. By default, the ls command lists the names of all files and directories in the current directory. The ls command is one of the basic commands that any Linux user should know.

2. **cd:** cd Linux command is used to change the current working directory. It is a built-in command, which means that it is included directly into the shell. The cd command is available in all shells, including cmd, bash, and PowerShell.

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


**INPORTANT:** the command ***ls -la*** will list all files in the current directory, including hidden files (The core of the challenge is to find the hidden file).


4. **cat** - Concatenate files and print on the standard output

**command example:**

```bash
cat filename
```


## Theory:

In Uniz is common t have files that are no "visible" in a simple way for the user, hackers used to call them "hidden files".They are hidden because they start with a dot (.) in their name.

Remember that a disabled simple "visibility" dosen't mean that the file is not there, you can access it using the correct command


## Solution:

**Warning:** Just see the solutions if you are stuck. Try harder to solve the challenges; that's the best way to learn.

<details>
<summary>Solution:</summary>

1. Once you are in the bandit2 level, write the following command:

```bash
cd ./inhere 
```

this commands change the current directory to the inhere directory.

2. Now display the content of the hidden file

```bash
cat ./...Hiding-From-You
```


**Tip:** Remember using tab ket as you best friend to autocomplete the name of the file.

2. The password for the next level will be displayed.

***Password: 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ**

</details>

### See u in the level  ;)
