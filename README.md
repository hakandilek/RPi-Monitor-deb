# RPi-Monitor-deb

**RPi-Monitor-deb** is the project packaging [**RPi-Monitor**](https://github.com/XavierBerger/RPi-Monitor) into a debian package. **RPi-Monitor** is a self monitoring application designed to run on [Raspberry Pi](http://www.raspberrypi.org/).

Installation, usage and customization are detailed into the official web site: [http://rpi-experiences.blogspot.fr/](http://rpi-experiences.blogspot.fr/)


## Prerequisite

Before using **RPi-Monitor-deb** it is required to install the dependencies. To do so, execute the following command:

    sudo apt-get install dpkg-dev 

## Package creation

Clone RPi-Monitor and RPi-Minitor-dev:

    git clone https://github.com/hakandilek/RPi-Monitor.git
    git clone https://github.com/hakandilek/RPi-Monitor-deb.git

Build package:

    cd RPi-Monitor-deb
    ./build-deb.sh
    
## Authors

**Xavier Berger**

+ [http://rpi-experiences.blogspot.fr](http://rpi-experiences.blogspot.fr)
