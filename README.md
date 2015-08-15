# raspberry-pi-ansible
Provision a new Raspberry Pi in "headless: mode using [Ansible](http://www.ansible.com/home). Without requiring a keyboard, mouse, or monitor to be connected. Great way to set it up for development and/or tests.

* Download the latest Raspbian image from https://www.raspberrypi.org/downloads/
```
$ cd /tmp
$ wget http://downloads.raspberrypi.org/raspbian_latest
$ tar -xzvf raspbian_latest
```
* Format SD card, follow the instructions on https://www.raspberrypi.org/documentation/installation/installing-images/
* Insert the SD card into RPi
* Insert the ethernet cable into the RPi
* Plug in the power supply
* SSH into the RPi by
```
$ ssh pi@raspberry     # pw: raspberry
```
