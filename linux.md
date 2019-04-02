# Useful commands
### install a debian pacakge

sudo dpkg -i "package name"

### Use Nordvpn
nordvpn connect/nordvpn c

nordvpn connect sg185

nordvpn set obfuscate on

nordvpn disconnect/nordvpn d

### Install atom  
sudo add-apt-repository ppa:webupd8team/atom

curl -sL https://packagecloud.io/AtomEditor/atom/gpgkey | sudo apt-key add -
sudo sh -c 'echo "deb [arch=amd64] https://packagecloud.io/AtomEditor/atom/any/ any main" > /etc/apt/sources.list.d/atom.list'

sudo apt-get install atom
