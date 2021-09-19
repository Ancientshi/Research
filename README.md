# How to run c programs in UNSW CSE LAB computer by VSCODE in remote mode 
- This guide is for **COMP9024**, we suppose that you have already known how to connect to the computer through SSH by VSCODE and this work is based on that.
- This simple guide **is only for reference**. There may be some inaccuracies. If you find anything, it is welcome to comment **friendly** in issue.
## File structure
This is the structure of c_example folder.
.
├── README.md   
├── inc
│   └── a.h
├── main
├── main.c
└── src
    └── a.c
This is the structure of .vscode folder which is under the same folder(~) with c_example.
.
├── c_cpp_properties.json
├── launch.json
└── tasks.json
## Install Extensions
C/C++ Extension Pack
C/C++
Code Runner
## Config Json files
1. open main.c, command+shift+p, then choose "Config Default Build Task". Then there will be a directory named .vscode created in your workspace and a json file named tasks.json created in the folder. 
2. open main.c, command+shift+p, then choose "C/C++ Edit Configurations(JSON)". There will be a json file named c_cpp_properties.json created in the folder.
3. You should change some lines in tasks.json and  c_cpp_properties.json. You can take my files as reference.
4. open main.c, then click Run and Debug button on the left of the VSCODE, then click create a launch.json file. here will be a json file named launch.json created in the folder.

## Build
open main.c, command+shift+b

## Debug
open main.c, then click Run and Debug button, then click Debugging.

