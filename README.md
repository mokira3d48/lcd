# Linux Command Lines

## Chromium browser
This is a web browser.

### Installation
```sh
sudo add-apt-repository ppa:savoury1/chromium;\
sudo apt update;\
sudo apt install chromium-browser
```

## kavintune
Compatible for KDE only.

### Installation
#### For KDE Ubuntu or Kubuntu
1. Installation of dependencies
```sh
sudo apt-get install g++ libx11-dev libxext-dev qtbase5-dev libqt5svg5-dev libqt5x11extras5-dev libkf5windowsystem-dev qttools5-dev-tools cmake checkinstall
```
2. Download the repository
```sh
git clone https://github.com/tsujan/Kvantum.git && cd Kvantum/Kvantum/
```
3. Compile and install the program on your machine.
```sh
mkdir build && cd build;\
cmake ..;\
make;\
sudo make install
```

#### For KDE Kali linux
```
sudo apt-get -y install qt5-style-kvantum
```

