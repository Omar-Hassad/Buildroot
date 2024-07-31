# Buildroot
Making Minimal Linux Distro with Buildroot
sudo apt update
sudo apt upgrade
sudo apt install -y git build-essential libncurses5-dev
Next, we need to clone the Buildroot repository:
cd ~
mkdir Projects
cd Projects
git clone git://git.buildroot.net/buildroot
cd buildroot
ls configs
make menuconfig
make
ls -la output/images
