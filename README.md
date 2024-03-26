# Git_setup
Getting started (b/c I'll forget how to set this up

# check if git is already installed using
git --version

# linux cmd to install git
apt install git

# Use whatever email and username is applicable.
git config --global user.email "jamesbennettwebb@gmail.com"
git config --global user.name "James"

# remote repositories using the url of the git repository to clone
# Support for password authentication was removed on August 13, 2021
# Connecting to github with SSH
ssh-keygen -t ed25519 -C "your_email@example.com"
# You will then be required to type a filename for the key to be saved in.
# Open the file.pub and copy ALL of the text.
# Login to github > Top right corner > Settings > SSH and GPG keys > New SSH key
# Add a title and past in your key (This will have your email at the end)

##ran out of time https://docs.github.com/en/authentication/troubleshooting-ssh/error-permission-denied-publickey?platform=linux is where I left off.##


#git clone https://github.com/jamesbwebb/seanwebbglass

# git init or git clone
# This initializes a new git repo in the cwd
git init
