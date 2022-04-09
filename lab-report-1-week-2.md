# **Lab Report 1**
## Step 1: Installing Visual Studio Code
Navigate to the Microsoft's website for [VSCode](https://code.visualstudio.com/download) and install the corresponding version for your operating system

In my case I use a Mac so I would install the Mac version

<img src="imgs/VSCodeSS1.png" width=50%>

---

## Step 2: Remotely Connecting
Open terminal on your system or powershell for Windows users

Here we use the **ssh** (secure shell) command to remotely connect UCSD's linux servers
> Windows users need to install ssh from [OpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)

From here we can continue to connect by typing in: `ssh (USERNAME)@ieng6.ucsd.edu`
> The username for the machines can be obtained from [sdacs](https://sdacs.ucsd.edu/~icc/index.php)

This will then prompt you for a password which once typed in will log you in

![Image](imgs/SSH%20login.png)

<img src="imgs/SSH login2.png" width = 50%>

---

## Step 3: Trying some commands
Now that you are connected to the remote server a few basic linux commands include

- pwd : prints the current working directory
- ls : prints the files and directories
- cd : navigates to a certain specified directory

Some of these commands such as ls have parameters that can be added by doing `ls -a` to list all directories and files including those that are hidden

A few uses of these commands are listed below

<img src="imgs/ssh commands.png" width = 50%>