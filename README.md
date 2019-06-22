# RaspberryPi-Zero:Getting Started
  The Raspberry PI Zero isn’t a low-calorie dessert: it's a member to the low-cost computer family from the Raspberry PI foundation. Even with a low cost of around $10, the Raspberry Pi Zero has a lot of features. The Pi Zero has Mini HDMI out, 1GHz processor, and 512Mb of RAM, which makes it quite a functional computer for such a low cost. The Pi Zero is 60% smaller than the Raspberry Model B+ version of the Pi. So lets get started on using **RPi Zero** through **WiFi**. Only "RPi Zero w" or later versions have an internal wireless LAN and Bluetooth Connectivity.
  
## HARDWARE REQUIREMENTS

* Raspberry PI zero (including at least USB adapater and power supply).
* 1 micro SD card (at least 8 GB, preferrably class 10) with an SD adapter.

(**Note** :- You will also need a **Wireless N Nano USB Adaptor** for RPi zero versions preceding RPi Zero w.)


## SOFTWARE REQUIREMENTS
* A disc image of [Raspbian Stretch](https://www.raspberrypi.org/downloads/raspbian/)
* [SD Card Formatter](https://www.sdcard.org/downloads/formatter/)
* An Image formatting software, for example [Win32DiskImager](https://sourceforge.net/projects/win32diskimager/)
* An SSH client like [PuTTY]()
* VNC Viewer, for example [REAL VNC](https://www.realvnc.com/en/connect/download/viewer/)

## Step-By-Step Procedure

**Step 1**: Insert your SD Card to an SD Card Reader and connect to your PC or Laptop. *Overwrite Format* the SD Card using the SD Card Formatter. Write the disc image of the Raspbian OS onto the SD Card using [Win32DiskImager](https://sourceforge.net/projects/win32diskimager/).

**Step 2**: Copy the [SSH]() file and [wpa_supplicant]() into the Boot: drive(**Note**:Use [Notepad ++]() and fill your WiFi Credentials in the wpa_supplicant.conf file before copying.). Eject the SD Card and place it inside the slot providded in the RPi Zero board.
(**Note**: RPi Zero recognizes UNIX EOL format. Windows users make sure to change to **EDIT**->**EOL Conversion**->**UNIX**. It is shown in the left bottom corner.)
