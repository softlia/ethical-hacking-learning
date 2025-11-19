# Day 3 Commands

# Create a practice folder
mkdir perm_lab
cd perm_lab

# Create files
touch file1 file2 script.sh
echo "echo hello" > script.sh

# View permissions
ls -l

# Change permissions
chmod 600 file1
chmod 644 file2
chmod 755 script.sh

# Remove execute permission
chmod -x script.sh
./script.sh   # should fail

# Add execute permission back
chmod +x script.sh
./script.sh   # should run

# Change ownership (user and group)
sudo chown $USER file1
sudo chgrp $USER file1

# View final permissions
ls -l

