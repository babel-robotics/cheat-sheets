## Terminal - Basics

| Debian | MacOS | Windows | Command | Flag | Comment |
|---|---|---|---|---|---|
|`sudo apt-get update`|-|-|-|-|updates the available pkg versions for apt from an online library|
|`sudo apt install <pkgname>`|-|-|-|-|installs a pkg if availabe from the Advanced Packaging Tool|
|`sudo apt-get upgrade`|-|-|-|-| upgrades all installed apt pkgs on your OS (may not be desired)|
|`apt-cache show <pkgname>`|-|-|-|-|shows available updates for the specified pkg|
|`apt-cache search <pkgname>`|-|-|-|-|searches for available pkgs in the apt-cache, the internal database in which information on all available packages is stored|
|`cd foldername`|-|-|change folder|-|-|
|`cd`&nbsp;`path/to/folder/foldername`|-|-| change dir|-| *dir = directory*|
|`cd ..`|-|-| change one dir level up|-|-|
|`cd ~`|-|-|change to home dir| -|-|
|`kill -9 processnumber`| - | - | kill process | - | kills the processes with the specified ID number |
|`killall nautilus`| - | - | kills nautilus | - | kills the nautilus file manager, usefull when nautlus crashes|
|`ls`|-|-|list files|-|-|
|`mkdir foldername`|-|-| make new folder| -|-|
|`mv filename path/filename`|-|-| move file to other dir|-|-|
|`mv filename newfilename`|-|-| rename file| -|-|
|  - | `open filename`   | - | open file in gui | - | -|
|`pkill keyword`| - | - | process kill | - | kills all processes containing the keyword |
|`ps`| - | - | processes | - | shows all currently running processes |
|`ps aux`| - | - | processes auxiliary | - | shows running processes with additional information like cpu usage |
|`ps aux \| grep 'keyword'`| - | - | processes, grep | - | searches within running processes for a specific keyword |
|`rm filename`|-|-| remove file or folder|-r |recursively|
|`touch file.txt`|-|-| make new .txt file| -| *or other file format*|
| `xdg-open` | `open path/foldername`   | - |open folder in gui  |  - |-|
|-|-|-|-|-|-|


