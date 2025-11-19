# Day 4 Commands

# View system users
cat /etc/passwd

# View groups
cat /etc/group

# Create a test user
sudo useradd testuser
sudo passwd testuser

# Create a group
sudo groupadd developers

# Add user to a group
sudo usermod -aG developers testuser

# Check groups for a user
groups testuser

# Switch user
su testuser
whoami
exit

