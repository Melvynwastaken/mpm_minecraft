# minecraft
Installation
Download the install.lua file to your in-game computer using the Pastebin get command. Replace pastebin_link with the link to the Pastebin.

wget run https://github.com/Melvynwastaken/mpm_minecraft.git
Run the install.lua script to install MPM. This script will automatically download the necessary package manager files from the MPM GitHub repository.

Usage
Once MPM is installed, you can use the following commands:

mpm tap_repository <repository url>: Add a new repository to your list of tapped repositories.
mpm install <package>: Install a package from the tapped repositories.
mpm update [package]: Update a specific package or all packages if no package name is provided.
mpm remove <package>: Remove a specific package.
mpm list: List all installed packages.
mpm run <package>: Run a specific package.
mpm self_update: Update the MPM system itself.
For instance, to install a package named my_package, you would use the command mpm install my_package.

As of writing this message I'm not finished and still working on it, I hope this might be of use to someone.
