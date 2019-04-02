## Install gcc 4.9
sudo add-apt-repository ppa:ubuntu-toolchain-r/test

sudo apt-get update

sudo apt-get install g++-4.9

### Configure gcc version
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.8 100
sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-4.8 100

sudo apt-get install gcc-4.9
sudo update-alternatives --install /usr/bin/gcc gcc /usr/bin/gcc-4.9 50
sudo apt-get install g++-4.9
sudo update-alternatives --install /usr/bin/g++ g++ /usr/bin/g++-4.9 50

sudo update-alternatives --config g++

## CMake
CMake is a system to generate make files based on the platform (i.e. CMake is cross platform) which you can then make using the generated makefiles. While make is you directly writing makefile for a specific platform that you are working with.
