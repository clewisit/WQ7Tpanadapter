# WQ7Tpanadapter
A very enhanced panadapter program for the Raspberrypi based on the original FreqShow

This version has been modified to fix indentation issues preventing it from working with
newer versions of python and the ability to demodulate/decode and output analog/digital 
audio (based on drewby08/FreqShow with additional improvements)

INSTALLATION of DEPENDENCIES
!VERY IMPORTANT!

Instructions updated for Raspberry Pi OS 64-bit Bullseye

Please note, the enhancements to the original FreqShow by WQ7T require the Python-Scipy
Library in addition to the original dependencies for FreqShow.

Original dependencies required by Adafruit/FreqShow
https://learn.adafruit.com/freq-show-raspberry-pi-rtl-sdr-scanner/installation
install scripts:

sudo apt-get update

sudo apt-get upgrade

sudo apt-get install cmake build-essential libusb-1.0-0-dev git pandoc rtl-sdr librtlsdr-dev

sudo apt-get install python3-numpy python3-scipy python3-matplotlib python3-ipython python3-pandas python3-sympy python3-nose

sudo pip3 install pyrtlsdr

INSTALL the WQ7Tpanadapter software 

cd ~
git clone https://github.com/clewisit/WQ7Tpanadapter.git

sudo cp -r WQ7Tpanadapter/FreqShow_Large FreqShow_Large

sudo cp -r FreqShow_Large/FreqShow.desktop Desktop/FreqShow.desktop

READ READ READ THE PDF operating manual it will also show you how to save your own deafault parameters!
