# linux-fundamental-wsl
DevOps assignment: Linux system administration tasks using WSL
### Screenshot 1: Ubuntu WSL Environment

This screenshot confirms that Ubuntu 24.04 LTS is running properly under Windows Subsystem for Linux (WSL).  
The command `lsb_release -a` was used to verify system info.

![Screenshot 1](screenshots/screenshot1.png)

### Screenshot 1: Ubuntu WSL Environment

This screenshot confirms that Ubuntu 24.04 LTS is running properly under Windows Subsystem for Linux (WSL).  
The command `lsb_release -a` was used to verify system info.

![Screenshot 1](screenshots/screenshot1.png)

### Screenshot 2: Linux Folder Structure

This screenshot shows the custom folder structure `/home/donald_dev/projects/devops`, created using the `mkdir -p` command.  
The file `test.sh` already exists in the `devops` folder and will be used in the next task.

![Screenshot 2](screenshots/screenshot2.png)

### Screenshot 3: File Permissions and Ownership

This screenshot shows how I used `chmod 764` to set file permissions on `test.sh`,  
and `chown root:donald_dev` to change ownership.  
The `ls -la` output confirms the permissions (`rwxrw-r--`) and ownership (`root:donald_dev`).

![Screenshot 3](screenshots/screenshot3.png)

### Screenshot 4: Package Installation with apt

This screenshot shows the installation of the `htop` system monitor using `sudo apt install htop`.  
The version was confirmed using `htop --version`, which verifies that the package was installed correctly.

![Screenshot 4](screenshots/screenshot4.png)

### Screenshot 5: Ping Test to Remote Server

This screenshot shows the use of `ping -c 4 google.com` to test internet connectivity from the WSL Ubuntu environment.  
It confirms that the virtual machine has outbound access to the internet.

![Screenshot 5](screenshots/screenshot5.png)
