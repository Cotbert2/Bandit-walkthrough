# Level 0 -> Level 1

**Description:** The goal of this level is for you to log into the game using SSH. The host to which you need to connect is bandit.labs.overthewire.org, on port 2220. The username is bandit0 and the password is bandit0. Once logged in, go to the Level 1 page to find out how to beat Level 1.

## Commands and common flags:

1. **ssh** - OpenSSH SSH client (remote login program)
    * **-p** - Port to connect to on the remote host
    * **-l** - Specifies the user to log in as on the remote machine

**command example:**

```bash
ssh -p $PORT $USER@$HOST
```

##Solution:

**Warning:** Just see the solutions if you are stuck. Try harder to solve the challenges; that's the best way to learn.

<details>
<summary>Solution:</summary>
```bash
ssh -p 2220 
```
</details>
