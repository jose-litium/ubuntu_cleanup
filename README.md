Certainly! Here's the updated README in plain text format with the additional instructions:

```
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
   ```

2. **Check Permissions:**
   Before executing the script, ensure it has the necessary permissions. Navigate to the directory containing `ubuntu_cleanup.sh` and verify its permissions using:
   ```
   ls -l ubuntu_cleanup.sh
   ```
   Ensure the output includes `-rwxr-xr-x` or similar (`rwx` for owner, `r-x` for group and others).

3. **Change Permissions:**
   If the script lacks execute permissions, add them using:
   ```
   chmod +x ubuntu_cleanup.sh
   ```
   This grants execute (`+x`) permissions to `ubuntu_cleanup.sh`.

4. **Execute the Script:**
   Run the script by entering:
   ```
   ./ubuntu_cleanup.sh
   ```
   Ensure you are in the same directory as the script. The `./` notation specifies the current directory.

5. **Handling Permission Denied (Optional):**
   If you encounter "Permission denied" even after changing permissions, consider using `sudo`:
   ```
   sudo ./ubuntu_cleanup.sh
   ```
   Enter your password if prompted, provided you have `sudo` privileges.

### Notes

- This script is intended for Ubuntu systems.
- Always review scripts before executing them to ensure they meet your security standards.
- Use caution when granting execute permissions (`chmod +x`) to scripts from untrusted sources.

Feel free to contribute to this project by submitting pull requests or reporting issues.
```

This plain text version includes all the steps and additional instructions as requested. You can copy and paste it directly into your README file for your Ubuntu cleanup and optimization repository.
