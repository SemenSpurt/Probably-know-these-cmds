# Find
find directory-to-search criteria action \
find ./ -type f -iname "*geneInfo*"

# List all users
cat /etc/passwd

# Delete user
sudo userdel -r <usename>

# Create new user 
sudo useradd -m -g <primary> -G <secondary,groups> -s /bin/bash <name> \
  -m creates user with home directory\
  -s creates user with specific shell\


# Change user`s password
sudo passwd <username>
