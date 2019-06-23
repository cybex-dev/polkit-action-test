# Polkit Action Test

The purpose of this script(s) is for anyone to run it, and see how 
[polkit](https://wiki.archlinux.org/index.php/Polkit) actions are handled in a Linux environment. 

**NOTE: Change the package manager
open the file `bin/subAppPacman` and change the line `pacman -Syyu` to that of your package manager**

| Distro                | Package Manager Install Command |
|-----------------------|---------------------------------|
| Debian/Ubunut/Mint:   |  ```apt install ${pkgName}```   |
| Redhat/Fedora/CentOS: |  ```yum install ${pkgName}```   |
| Arch:                 |  ```pacman -Syu```              |

*Reason for the pacakage manager is this is a confirmed root user action, but it can be replaced with any action requiring root user priviledges*

Hope this helps :)
