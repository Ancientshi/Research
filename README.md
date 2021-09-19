# How to run c programs in UNSW CSE LAB computer by VSCODE in remote mode 
- This guide is for **COMP9024**, we suppose that you have already known how to connect to the computer through SSH by VSCODE and this work is based on that.(You can see https://github.com/Ancientshi/Master-Learning/blob/master/VSCODE_connect_to_CSE.md)
- This simple guide **is only for reference**. There may be some inaccuracies. If you find anything, it is welcome to comment **friendly** in issue.
## File structure
This is the structure of c_example folder. The folder .vscode is for reference, it is not necessary for running you own c programs. When your configuration is finished and run c program well, you can delete the folder.
```
.
├── .vscode   
    ├── c_cpp_properties.json
    ├── launch.json
    └── tasks.json
├── README.md   
├── inc
│   └── a.h
├── main
├── main.c
└── src
    └── a.c
```
## Install Extensions
C/C++ Extension Pack
C/C++
Code Runner
## Config Json files
1. Open main.c, command+shift+p, then choose "Config Default Build Task". Then there will be a directory named .vscode created in your workspace and a json file named tasks.json created in the folder. 
2. Open main.c, command+shift+p, then choose "C/C++ Edit Configurations(JSON)". There will be a json file named c_cpp_properties.json created in the folder.
3. You should change some lines (8, 13, 16) in tasks.json, and line (8) in c_cpp_properties.json. You can take my files as reference. (You should use your own path)
4. Open main.c, then click Run and Debug button on the left of the VSCODE, then click create a launch.json file. here will be a json file named launch.json created in the folder.

## Build
Open main.c, command+shift+b

## Debug
Open main.c, then click Run and Debug button, then click Debugging.

