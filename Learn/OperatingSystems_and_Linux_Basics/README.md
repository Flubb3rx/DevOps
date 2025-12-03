Operating Systems and Linux Basics


When installing Oracle VM VirtualBox Extension Pack on the virtual machine, you might encounter the following error:
"This system is currently not set up to build kernel modules.
Please install the gcc make perl packages from your distribution."

To fix this, run the commands below one by one:

sudo apt-get update
sudo apt-get install build-essential gcc make perl dkms
reboot
