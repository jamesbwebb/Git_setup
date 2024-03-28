# Git_setup
Getting started (b/c I'll forget how to set this up

# check if git is already installed using
git --version

# linux cmd to install git
apt install git

# Use whatever email and username is applicable.
git config --global user.email "jamesbennettwebb@gmail.com"
git config --global user.name "jamesbwebb"

cd ~/.ssh
ssh-keygen -o -i rsa -C "<Your email here>"
# I set this up without adding folders or a special key that I will forget.

ls # We are looking for the .pub file contents
cat is_rsa.pub

# Copy this and paste it into gethub.
# Login, button in top right corner, settings,
# ssh and gpg keys, create new, paste in here and add a title.

# Then in the web browser, go to the directory we want to clone.
# Click on the "Code" dropdown, "Local" tab, SSH and copy the git@github.com line
git clone <paste the above line here>

# At this point we can pull and push from the remote repository.
