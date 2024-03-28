# Git_setup
# Getting started (b/c I'll forget how to set this up
# check if git is already installed using
git --version

if git == installed:
  continue
else:
  # linux cmd to install git
  apt install git

# set up git in your CWD, move the the one you want first
git init

# Use whatever email and username is applicable. We are using the global tag to cover all git repos
git config --global user.email "jamesbennettwebb@gmail.com"
git config --global user.name "jamesbwebb"

# If we are setting up a local repo add all of your stuff.
git add <file or folder>
# Then we git push to add it to our online repo
git push --set-upstream git@github.com:jamesbwebb/seanwebbglass.git master

#Setting up ssh key with github.com
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

# At this point we put a subdirectory in our cwd that is our git hub repo
# problem is I don't want to do that.

# At this point we can pull and push from the remote repository.
