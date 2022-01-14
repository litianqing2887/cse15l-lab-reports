# **Installing VScode**
1. Go to [VScode website](https://code.visualstudio.com/).
2. Click "Download" at the upper right connor.
![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/VScode.png?raw=true)
# **Remotely Connecting**
1. Set up OpenSSH in Apps > Optional features. 
![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/Open%20ssh.png?raw=true)
2. In Terminal, input "ssh id@ieng6.ucsd.edu".
3. Input password.
![Image](https://raw.githubusercontent.com/litianqing2887/cse15l-lab-reports/c628b3e908447ecbaec2de8679f89faa8dfbd55e/ssh.png)
# **Trying Some Commands**
1. ls List the current directory.
2. cd Change directory.
3. cp Copy the file. 
![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/command.png?raw=true)
# **Moving Files with scp**
* scp file_name target_directory
![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/scp.png?raw=true)
# **Setting an SSH Key**
1. Generate SSH key pair. [How](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_keymanagement#user-key-generation)
2. Use scp to cope the public key into server.
3. Try to login without password.
![Image](https://github.com/litianqing2887/cse15l-lab-reports/blob/main/ssh%20key.png?raw=true)
# **Optimizing Remote Running**
* Login, command, and exit.

  *ssh account "command"*
* Use semicolons to connect many commands in one line.

  *command1;command2;command3*
