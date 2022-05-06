## Streamlining ssh Configuration

**To open the config file, type in ```~/.ssh/config``` in the terminal of VS Code**

![](R3P1.png)

You should be able to see something like this:

![](R3P2.png)

Now, in the VS code, add ```User cs15lsp22zzz``` where ***zzz*** are the unique 3 letters assigned to you

![](R3P3.png)

Once you've done that, you should be able to log into your server using ```ssh ieng6```

![](R3P4.png)

To copy a file from client server to remote server, use the following command: ```scp (file_name) ieng6:```

![](R3P5.png)

## Copying Whole Directories

**Instead of copying all files individually, we can copy all files at once using the following command**

Let ***dir*** be the name of the directory you want to copy, enter the following command: 

```scp -r . cs15lsp22zzz@ieng6.ucsd.edu:~/dir``` where ***zzz*** is your unique code 

You should see something like this

![](R3P6.png)