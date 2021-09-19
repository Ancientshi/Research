# how to connect to CSE computer without password and write code by vscode in remote mode 
This is a quick guide.（Maybe not very detailed）
UNSW give a guide: https://abiram.me/cse-setup, you can also see it.
## Install vscode
https://code.visualstudio.com/

## Install extensions
The following extensions are required.
Remote - Containers
Remote - SSH
Remote - SSH: Editing Configuration Files
Remote - WSL
Remote Development

## config
1. In vscode, click the remote explorer button, then find SSH TARGETS, on the right, there is a configure button and you need to click it.
2. Write the following to .ssh/config file and save. (you need to use your own zid to replace z0000000)
```
HOST UNSW_CSE
HostName login.cse.unsw.edu.au
User z0000000
```

## login
1. There will be a UNSW_CSE SSH target, you can open it.
2. Then you need to type your password.

## login without password
1. in cse terminal. 
2. type linux commands: ssh-keygen -t rsa, there will be a folder '.ssh',type linux commands: cd .ssh
4. type linux commands: touch authorized_keys
5. in your computer, in .ssh folder, type linux commands: cat id_rsa.pub, copy the content
6. open the authorized_keys file in cse, and paste the content in this file, save.
7. Then you are not required to type a password to connect to the CSE.