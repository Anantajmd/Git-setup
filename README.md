# Git-setup
Git setup on local system

## Install Git on Windows
#### Git for Windows stand-alone installer
1) Download the latest Git for Windows installer.

2) When you've successfully started the installer, you should see the Git Setup wizard screen. Follow the Next and Finish prompts to complete the installation. The default options are pretty sensible for most users.

3) Open a Command Prompt (or Git Bash if during installation you elected not to use Git from the Windows Command Prompt).

4) Run the following commands to configure your Git username and email using the following commands, replacing Emma's name with your own. These details will be associated with any commits that you create:

 
$ git config --global user.name "Emma Paris" $ git config --global user.email "eparis@atlassian.com"


## Install Git on Linux
#### Debian / Ubuntu (apt-get)
#### Git packages are available via apt:

1) From your shell, install Git using apt-get:
   $ sudo apt-get update
   $ sudo apt-get install git

2) Verify the installation was successful by typing git --version:
i) $ git --version
   git version 2.9.2

3) Configure your Git username and email using the following commands, replacing Emma's name with your own. These details will be associated with any commits that you      create:
i) $ git config --global user.name "Emma Paris"
ii) $ git config --global user.email "eparis@atlassian.com"
