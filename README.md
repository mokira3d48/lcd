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
1. Installation of dependencies
```sh
sudo apt-get install g++ libx11-dev libxext-dev qtbase5-dev libqt5svg5-dev libqt5x11extras5-dev libkf5windowsystem-dev qttools5-dev-tools cmake checkinstall
```
2. Download the repository
```sh
git clone
```
3. Compile and install the program on your machine.
```sh
mkdir build && cd build;\
cmake ..;\
make;\
sudo make install
```
