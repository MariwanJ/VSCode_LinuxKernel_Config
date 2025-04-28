# VSCode_LinuxKernel_Config
C/C++ configuration file for importing includes for Linux kernel development using Visual Studio Code on Linux.


## Instructions
### Location: 
Place the configuration file in the .vscode folder within your project directory. If the .vscode folder does not exist, create it.

### Update: 
You may need to update the contents of the file if the files in the linux-headers folder change.
### These Two Lines might need modifications depending on your system:
                "/usr/src/linux-headers-5.10.0-34-amd64/**",
                "/usr/src/linux-headers-5.10.0-34-common/**"

### Functionality: 
The JSON file will attempt to import all header files and their subfolders.


Mariwan Jalal 2025-04-28
