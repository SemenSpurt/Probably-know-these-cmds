# List all users
cat /etc/passwd

# Delete user
sudo userdel <usename>

# Create new user 
sudo useradd -m -g <primary> -G <secondary,groups> -s /bin/bash <name> \
  -m creates user with home directory\
  -s creates user with specific shell\


# Change user`s password
sudo passwd <username>
