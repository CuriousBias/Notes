# Linux

sudo apt update        # Fetches the list of available updates
sudo apt upgrade       # Installs some updates; does not remove packages
sudo apt full-upgrade  # Installs updates; may also remove some packages, if needed

apt list --upgradable  # list upgradeable packages
sudo apt upaate  # update information about sw versions and available updates
sudo apt upgrade. # update some software
sudo apt full-upgrade →y # apt upgrade plus add and remove dependencies as needed. Alias for dist-upgrade sudo apt autoremove
* remove any no longer needed dependencies
sudo apt clean # removed cached packages
sudo do-release-upgrade # actually update to next major version 20.04 → 22.04


