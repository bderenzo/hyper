# Hyper

## Description 

This script prepare and configure a fresh debian or raspbian installation into a tiny lxc hypervisor.

The script can: 
* Install sysadmin packages (htop, wget, ...)
* Clean raspberrypi useless packages
* Replace hostname
* Configure host bridge
* Configure /tmp ro ram
* Configure /var/log to ram
* Install and preconfigure lxc
* Configure lxc with lvm disk
* Install lxc manager (lxm)

## Setup 

To user hyper script, with root rights: 

* Clone the repo
* Edit `./hyper.conf` and complete configuration
* Run `./install` and follow the instruction

