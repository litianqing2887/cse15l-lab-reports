# **Installing VScode**
* Go to [VScode website](https://code.visualstudio.com/).
* Click "Download" at the upper right connor.
![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/VScode.png?raw=true)


# **Remotely Connecting**
* Set up OpenSSH in Apps > Optional features. 
![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/Open%20ssh.png?raw=true)

* In Terminal, input "`ssh` id@ieng6.ucsd.edu".
* Input password.

![Image](https://raw.githubusercontent.com/litianqing2887/cse15l-lab-reports/c628b3e908447ecbaec2de8679f89faa8dfbd55e/ssh.png)



# **Trying Some Commands**
* `ls` List the current directory.
* `cd` Change directory.
* `cp` Copy the file. 

![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/command.png?raw=true)

# **Moving Files with scp**
* `scp` file_name target_directory

  The file should be in local PC.
![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/scp.png?raw=true)


# **Setting an SSH Key**
* Generate a SSH key pair. [How](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_keymanagement#user-key-generation)
* Use `scp` to copy the public key into server.
* Try to login without password.
![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/ssh%20key.png?raw=true)

* Type commands without put in password. 
![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/ssh%20command.png?raw=true)


# **Optimizing Remote Running**
* Login, command, and exit.

  *`ssh` account "command"*
* Use semicolons to connect many commands in one line.

  *command1;command2;command3*
  
* Total keystroks *
  *5 times, very convenient*
