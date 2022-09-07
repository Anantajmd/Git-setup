# Git-setup
Git setup on local system

## Install Git on Windows
#### Git for Windows stand-alone installer
1) Download the latest Git for Windows installer.

2) When you've successfully started the installer, you should see the Git Setup wizard screen. Follow the Next and Finish prompts to complete the installation. The default options are pretty sensible for most users.

3) Open a Command Prompt (or Git Bash if during installation you elected not to use Git from the Windows Command Prompt).

4) Run the following commands to configure your Git username and email using the following commands, replacing Emma's name with your own. These details will be associated with any commits that you create:

 
  $ git config --global user.name "tatya vinchu" 

  $ git config --global user.email "tatyavinchu@gmail.com"


## Install Git on Linux
#### Debian / Ubuntu (apt-get)
#### Git packages are available via apt:

1) From your shell, install Git using apt-get:
   
   $ sudo apt-get update
   
   $ sudo apt-get install git

2) Verify the installation was successful by typing git --version:

   $ git --version
   
   git version 2.9.2

3) Configure your Git username and email using the following commands, replacing Emma's name with your own. These details will be associated with any commits that you      create:

   $ git config --global user.name "tatya vinchu" 
   
   $ git config --global user.email "tatyavinchu@gmail.com"

## SSH key
##### Generate a new SSH key on your local machine. After generating the key,  add the key to your account on GitHub.com to enable authentication for Git operations over SSH.
1) Open Terminal.

2) Paste the text below, substituting in your GitHub email address.

   $ ssh-keygen -t ed25519 -C "your_email@example.com"
##### Note: If you are using a legacy system that doesn't support the Ed25519 algorithm, use:

   $ ssh-keygen -t rsa -b 4096 -C "your_email@example.com"
   
This creates a new SSH key, using the provided email as a label.
