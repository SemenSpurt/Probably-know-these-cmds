# Show configuration
git config --list

# Set email and name
git config --global user.name "WatsYourNameBuddy" \
git config --global user.email "YourEmailAddress"

# Configure SSH connection
ssh-keygen -t ed25519 -C "YourEmailAddress" \
eval $(ssh-agent) # make shure ssh-agent is running \
ssh-add ~/.ssh/id_rsa.pub

## Add SSH key to GitHub
Settings >> SSH and GPG keys >> New SSH key >> enter key from ~/.ssh/file.pub

# Generate Personal Access Token
Settings >> Developer Settings >> Personal access tokens >> 
Chose token type >> Generate new token >> Don`t forget checkboxes

# New repo
mkdir <project_dir-name> \
git init \
git remote add origin <remote repo URL> \
***write some code*** \
git add * \
git commit -am "commit title" \
git push --set-upstream origin master



