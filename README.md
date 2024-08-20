markdown
Copiar código
# Ubuntu System Cleanup and Optimization

This repository contains scripts for cleaning and optimizing Ubuntu systems.

## Scripts

### `ubuntu_cleanup.sh`

This script performs the following tasks:

- Updates package repositories and upgrades installed packages.
- Installs essential packages like `wget`, `git`, and `nano`.
- Cleans up package cache and removes unnecessary packages.
- Increases VRAM allocation (example command).

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/jose-litium/ubuntu-cleanup.git
   cd ubuntu-cleanup
Check Permissions:
Before executing the script, ensure it has the necessary permissions. Navigate to the directory containing ubuntu_cleanup.sh and verify its permissions using:

bash
Copiar código
ls -l ubuntu_cleanup.sh
Ensure the output includes -rwxr-xr-x or similar (rwx for owner, r-x for group and others).

Change Permissions:
If the script lacks execute permissions, add them using:

bash
Copiar código
chmod +x ubuntu_cleanup.sh
This grants execute (+x) permissions to ubuntu_cleanup.sh.

Execute the Script:
Run the script by entering:

bash
Copiar código
./ubuntu_cleanup.sh
Ensure you are in the same directory as the script. The ./ notation specifies the current directory.

Handling Permission Denied (Optional):
If you encounter "Permission denied" even after changing permissions, consider using sudo:

bash
Copiar código
sudo ./ubuntu_cleanup.sh
Enter your password if prompted, provided you have sudo privileges.

Notes
This script is intended for Ubuntu systems.
Always review scripts before executing them to ensure they meet your security standards.
Use caution when granting execute permissions (chmod +x) to scripts from untrusted sources.
