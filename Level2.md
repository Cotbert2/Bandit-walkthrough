# Level 2 -> Level 3

**Description:** The password for the next level is stored in a file called spaces in this filename located in the home directory


## About Commands:
1. **cat:** Cat command is used to concatenate and display the content of files. It can also be used to concatenate and display files. The cat command is mostly used for viewing the content of a file but it can also be used to create a new file, concatenate files, and redirect output in terminal. 
In simple words, the cat command is used to display the content of a file.

2. **ls:** The ls command is used to list the files and directories in the current directory. By default, the ls command lists the names of all files and directories in the current directory. The ls command is one of the basic commands that any Linux user should know.

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


3. **cat** - Concatenate files and print on the standard output

**command example:**

```bash
cat filename
```



## Solution:

**Warning:** Just see the solutions if you are stuck. Try harder to solve the challenges; that's the best way to learn.

<details>
<summary>Solution:</summary>

(optional) You can use the following command to list all files in the current directory:

```bash
ls -la
```


1. Once you are in the bandit2 level, write the following command:

```bash
cat ./spaces\ in\ this\ filename 
```

**Tip:** in the terminal just write cd ./spa and press tab to autocomplete the name of the file; using bash is a very common practice use tab ket to autocomplete teh name of the file.

2. The password for the next level will be displayed.

***Password: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx***

</details>

### See u in the level 2 ;)
