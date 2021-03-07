# dmenu - dynamic menu
---
dmenu is an efficient dynamic menu for X.


## Requirements
---
In order to build dmenu you need the Xlib header files.


## Installation
---
Edit config.mk to match your local setup (dmenu is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install dmenu
(if necessary as root):

```
make clean install
```

## Running dmenu
---
See the man page for details.

## Patches
---
I applied the following patches to my custom build and included their
corresponding diff files in the patches directory:

* dmenu-border-4.9
* dmenu-caseinsensitive-5.0
* dmenu-center-4.8
* dmenu-mousesupport-5.0
* dmenu-numbers-4.9
* dmenu-scroll-20180607-a314412
* dmenu-xresources-4.9
