# dev-on-windows
I work on the Windows platform, because many of the companies I work for, use apps that only run windows, and I use windows applications. However beeing a developer, unix tools such git and others just works better in a unix like environment. 


# install Choco to install things
https://chocolatey.org/install 

In a CMD with Admin rights
   choco install virtualbox
   choco install vagrant

#Initializing a fresh unix-like environment

Copy the content from my dropbox, but first things first

`export dropbox_home=/c/Users/Andreas/Dropbox`

Check it

`ls $dropbox_home`

Copy the git keys

`cp $dropbox_home/Cygwin/homedir/.ssh/* .ssh/`

Check it 

`ssh -vT git@github.com`  

`ssh-add -l`

set permissions to your SSH folder
`chown 0600 ~/.ssh/*`

# Working with Vagrant boxes

Remember to set the hostname in the host file
e.g 127.0.0.1 bildelspriser.dev
