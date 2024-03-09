# Show configuration
git config --list

# Set email and name
git config --global user.name "WatsYourNameBuddy"
git config --global user.email "YourEmailAddress"

# Configure SSH connection
ssh-keygen -t ed25519 -C "YourEmailAddress"
eval $(ssh-agent) # make shure ssh-agent is running
ssh-add ~/.ssh/id_rsa.pub

# Generate Personal Access Token
Settings >> Developer Settings >> Personal access tokens >> 
Chose token type >> Generate new token >> Don`t forget checkboxes



