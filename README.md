# git-settings

Contains Git repo settings - Informations refered from TheOdins Project

Setup Git
git config --global user.name "Your Name"
git config --global user.email "yourname@example.com"

git config --global init.defaultBranch main

git config --global color.ui auto

git config --get user.name
git config --get user.email

Creating an SSH Key

ls ~/.ssh/id_ed25519.pub
ssh-keygen -t ed25519 -C <youremail> 
  
Linking of SSH Key with GitHub
  Go to settings -> SSH and GPG Keys -> new SSH Key
  cat ~/.ssh/id_ed25519.pub
  Copy everything which starts from ssh-ed25519
  
 Cloning of Respository
  Set up repository in github browser
  Take the link from ssh 
  then git clone 
  
