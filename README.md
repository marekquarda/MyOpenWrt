#  Programování MIPS QCA9533 - router TP-Link 
https://www.youtube.com/watch?v=eRus6Ncm7Dk
https://git.openwrt.org/?p=project/firmware-utils.git;a=tree;f=src;hb=ffd07b161d59adf2cea577eec0468496f66e6e5e

# Install GCC C++ on Ubuntu 22.04
cd Desktop/
mkdir install_g++-4.8
cd install_g++-4.8/
sudo apt update
wget http://mirrors.kernel.org/ubuntu/pool/universe/g/gcc-4.8/g++-4.8_4.8.5-4ubuntu8_amd64.deb 
wget http://mirrors.kernel.org/ubuntu/pool/universe/g/gcc-4.8/libstdc++-4.8-dev_4.8.5-4ubuntu8_amd64.deb 
wget http://mirrors.kernel.org/ubuntu/pool/universe/g/gcc-4.8/gcc-4.8-base_4.8.5-4ubuntu8_amd64.deb 
wget http://mirrors.kernel.org/ubuntu/pool/universe/g/gcc-4.8/gcc-4.8_4.8.5-4ubuntu8_amd64.deb 
wget http://mirrors.kernel.org/ubuntu/pool/universe/g/gcc-4.8/libgcc-4.8-dev_4.8.5-4ubuntu8_amd64.deb 
wget http://mirrors.kernel.org/ubuntu/pool/universe/g/gcc-4.8/cpp-4.8_4.8.5-4ubuntu8_amd64.deb 
wget http://mirrors.kernel.org/ubuntu/pool/universe/g/gcc-4.8/libasan0_4.8.5-4ubuntu8_amd64.deb  
sudo apt install ./gcc-4.8_4.8.5-4ubuntu8_amd64.deb ./gcc-4.8-base_4.8.5-4ubuntu8_amd64.deb ./libstdc++-4.8-dev_4.8.5-4ubuntu8_amd64.deb ./cpp-4.8_4.8.5-4ubuntu8_amd64.deb ./libgcc-4.8-dev_4.8.5-4ubuntu8_amd64.deb ./libasan0_4.8.5-4ubuntu8_amd64.deb ./g++-4.8_4.8.5-4ubuntu8_amd64.deb

# Repair to version 4.8
sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-4.8 10
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.8 10

# Install python 2 
sudo apt update
sudo apt install python2

# Install packages 



# Download OpenWrt 



 ./scripts/feeds update -a


