# Lab Report 1 by Jezebel Yangari

## 1) Installing VScode
> Make sure to install VSCode onto computer. This should be done before starting. 
![Image](Installing%20VScode.png)

## 2) Remotely Connecting
> Install OpenSSH. Then, in order to remotely connect, log in the the lab computer from your laptop by using VS Code's remote host feature with the `ssh` command + your ieng6 account address. When prompted enter password.
![Image](Screen%20Shot%202022-04-01%20at%2010.29.01%20AM.png)


## 3) Trying Some Commands
> I personally ran the commands `ls -a` and `ls` to test out. The `ls -a` command opening the list of the current directory and hidden files. The `ls` command shows files and sub directories in the directory I was currently in.
![Image](Screen%20Shot%202022-04-08%20at%2011.35.38%20AM.png)


## 4) Moving Files with scp
> Use the `exit` command to log out of my ieng6. Here the `scp` command is used to move files in my computer to a remote one. For example, type `_scp <FILE NAME>.java <username>@ieng6.ucsd.edu:~/_` .
![Image](Screen%20Shot%202022-04-08%20at%2011.36.52%20AM.png)


## 5) Setting an SSH Key
> In this step I set the **SSH Key** to prevent from having to always type my password. I replaced my password with a pair of public and private key files. The **ssh** command then uses those as my password.
![Image](Screen%20Shot%202022-04-08%20at%2011.59.49%20AM.png)


## 6) Optimizing Remote Running
> At end of an **ssh** command, write a command in quotation marks to directly run it on the remote server, then use exit command or Ctrl+D. One line consisted of running and compiling the WhereAmI.java file.
![Image](Screen%20Shot%202022-04-08%20at%2011.40.38%20AM.png)

References: Lab 1 Write Up
