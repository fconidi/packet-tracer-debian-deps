# Description

This repository fixes for running Cisco Packet Tracer on Debian 13 codename Trixie and SysLinuxOS 13 codename Tirreno. 

> Note: The `.deb` package included in this repository are official Debian packages and are distributed under their respective licenses.



## Tested ✅

- [x] SysLinuxOS 13
- [x] Debian 13



## Installation Steps


### Step 1: Clone the Repository


git clone https://github.com/fconidi/packet-tracer-debian-deps.git


### Step 2: Install Required Dependencies

cd packet-tracer-debian-deps/
sudo dpkg -i libgl1-mesa-glx_22.3.6-1+deb12u1_amd64.deb
sudo apt install -f

### Step 3: Download Cisco Packet Tracer 8.2.2

1) You can download the Cisco Packet Tracer 8.2.2 .deb package from the official Cisco Networking Academy website. Be sure to log in to your account before downloading.
Visit the [Cisco Networking Academy](https://www.netacad.com/) and download the Packet Tracer 8.2.2 version for Linux.

2) You can download directly from 

https://www.computernetworkingnotes.com/ccna-study-guide/download-packet-tracer-for-windows-and-linux.html

### Step 4: Install Cisco Packet Tracer

Once you have downloaded the .deb package, navigate to the directory where the .deb file is located. Install Packet Tracer using the following command:

sudo dpkg -i packettracer_8.2.2_amd64.deb
or
sudo dpkg -i CiscoPacketTracer822_amd64_signed.deb

enjoy ;)
