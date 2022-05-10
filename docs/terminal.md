## Terminal - Debian

| Command | Comment | Flag | Comment |
|---|---|---|---|
|`sudo apt-get update`|updates the available *pkg* versions for *apt* from an online library|-|-|
|`sudo apt install <pkgname>`|installs a *pkg* if availabe from the Advanced Packaging Tool|-|-|
|`sudo apt-get upgrade`|upgrades all installed *apt pkgs* on your OS *(may not be desired)*|-|-|
|`apt-cache show <pkgname>`|shows available updates for the specified *pkg*|-|-|
|`apt-cache search <pkgname>`|searches for available *pkgs* in the apt-cache, the internal database in which information on all available packages is stored|-|-|
|`cd foldername`| change folder|-|-|
|`cd`&nbsp;`path/to/folder/foldername`| change directory|
|`cd ..`| change dir to one level up|-|-|
|`cd ~`| change to home dir| -|-|
|`grep -rnw '/path/to/somewhere/' -e 'pattern'`| search through files for a pattern | -r| recursively |
| - | - | -n | line number|
| - | - | -w | match the whole word|
| - | - | -l | just give the file name of matching files|
| - | - | -e | the pattern used during the search|
|`kill -9 processnumber`| kills the processes with the specified ID number |-|-|
|`killall nautilus`| kills the nautilus file manager, usefull when nautilus crashes|-|-|
|`ls`|list files|-|-|
|`mkdir foldername`| make new folder| -|-|
|`mv filename path/filename`| move file to other dir|-|-|
|`mv filename newfilename`| rename file| -|-|
|`pkill keyword`| kills all processes containing the keyword |-|-|
|`ps`| shows all currently running processes |-|-|
|`ps aux`| shows running processes with additional/auxiliary information like cpu usage |-|-|
|`ps aux \| grep 'keyword'`|  searches within running processes for a specific keyword |-|-|
|`rm filename`| remove file or folder|-r |recursively|
|`touch file.txt`| make new .txt file *(or other file format)*| -|-|
| `xdg-open` | open folder in gui | -|-|
|-|-|-|-|

## Terminal - MacOS

| MacOS | Command | Flag | Comment |
|---|---|---|---|
|  `open filename`   |  open file in gui | - | - |
| `open path/foldername`   | open folder in gui  |  - | - |
|-|-|-|-|



