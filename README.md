# debian-install
Resources for installing debian on a new system

## Basic Instructions:

1. Add user to sudo
  * Ctrl-Alt-F1 and login as root
  * sudo adduser james sudo
2. Change window manager to gnome classic in login screen
3. Update apt repository and install all updates
4. If nvidia properatary driver is required:
  * Instructions [here](https://wiki.debian.org/NvidiaGraphicsDrivers)
  * Once installed, may have to manually edit xorg.conf to get 2nd monitor working.
  * See xorg.conf files in this git repo.
5. Enable Ctrl-Alt-Backspace by running dpkg-reconfigure keyboard-configuration
6. Add Alt-F2 custom shortcut for terminal in keyboard settings
7. List of software to install:
  * Chrome and lastpass extension
    * Enable Markdown preview plus access to file URLs in chrome://extensions
  * git
    * Generate new ssh key and add to github (see [guide](https://help.github.com/articles/generating-ssh-keys/))
  * Sublime Text
  * kicad
  * eagle
  * android studio
  * arduino
  * scons
  * virtualenvwrapper

