## Remotely Connecting 

We use **Secure Shell (sch)** to securely connect to the remote servers

To connect to remote servers, enter the following command in the terminal of your computer:

**ssh (user_name)@ieng6.ucsd.edu** where (user_name) is the user name assigned to you.

After completing the above step, you will be prompted to enter you password. Note: *The password you enter will not be visible, not even astriks, but it will be registered.*

After you enter your password and press enter/return, you will be logged into the remote server.

![After you've logged into the servers, you should be able to see something like this:](step3.png)



## Some Commands

A few of the commands that we can do on the remote server are:

* **pwd** This command prints the current working directory

* **ls** This command lists down all files and directories in the current directory

* **cd (directory_name)** This changes the directory to the specified (directory_name)

* **cd ~** This changes the current directory to home directory

* **ls (directory)** This lists down all files and directories in the specified (directory)

* **cat (file_name)** This prints the contents of the file

* **cp (file_1) (file_2)** This copies the contents of (file_1) to (file_2)

All the above commands should look like this in the terminal:

![](rep2.png)

## Moving Files from Client to Server

We use the **Secure Copy (scp)** command to securely copy files files from client to the server

To transfer files from client to a remote server, type in the following command in the terminal of your client:

**scp (file_name) (user_name)@(server_name):** where

* *(file_name)* is the name of the file you want to transfer. Note: Make sure that file is in the current working directory of your terminal

* *(user_name)* is the user name assigned to you

* *(server_name)* is the name of the server. In our case, server name is ieng6.ucsd.edu

* Note: Do not forget the colon at the end

Once you complete the above step, you should have transferred the files to your remote server and should be able to see something like this:

![](rep1.png)