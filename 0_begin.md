# Level 0

**Description:** The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

## About Commands:
1. **ssh:** ssh (secuere shell) is a secure protocol used to connect to a remote computer. It is widely used by network administrators to control Web and other kinds of servers remotely. It is also used to transfer files from one computer to another computer over the network using a secure copy (SCP) Protocol. 

## Commands and common flags:

1. **ssh** - OpenSSH SSH client (remote login program)
    * **-p** - Port to connect to on the remote host
    * **-l** - Specifies the user to log in as on the remote machine


**command example:**

```bash
ssh -p $PORT $USER@$HOST
```

## Solution:

**Warning:** Just see the solutions if you are stuck. Try harder to solve the challenges; that's the best way to learn.

<details>
<summary>Solution:</summary>
1. Open the terminal and type the following command.

```bash
ssh -p 2220 bandit0@bandit.labs.overthewire.org
```

2. Write "bandit0" on the password field.

</details>

### See u in the level 1 ;)
