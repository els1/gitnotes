Welcome to the GIT research computing workshop

Installing

MAC OSX - https://sourceforge.net/projects/git-osx-installer/files/
(pick most recent -- if works you should be able to type "git" at the command line)

Windows - should already be installed from bash workshop, if you weren't there
https://git-for-windows.github.io/

Linux - possibly already installed, if "git" at the command doesn't work
Ububtu/Debian: sudo apt-get install git
Fedora: sudo dnf install git

# Configuration 

Global configuration stored under ~/.gitconfig. Local configuration store$ 

```bash 
git config --global user.name "Tyson Whitehead"
git config --global user.email "twhitehead@gmail.com" 
```
```bash
git config --global color.ui auto
```
```bash 
git config --global core.editor nano
```

# Initialization 

Creates the .git directory. To undo `rm -r .git`. 

```bash 
mkdir $folder
cd $folder
git init
```
