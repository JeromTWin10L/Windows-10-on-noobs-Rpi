# Windows on noobs 
Introducing The Windows 10 installed with Pinn (like NOOBS)
## Installation Requirements
Raspberry Pi 3 B/B+ (for Raspberry pi 4b/400 coming soon!)

Power Supply 5v 2Ah (recommended 5v 2.5Ah)

Network 3.6G long

Sd card only supported 32G

Android/Windows/Linux/MAC

## Installation
### Installation (Linux,MAC)
Open Terminal

 And Become root user

 Run `apt update && apt install p7zip p7zip-full` to install depends

 Run `mkdir Recovery && mount /dev/<block device of sdcard> Recovery`

 Run `cd Recovery && 7z x /path/to/PINN_Lite.7z`

After extraction 

Run `cd .. && umount Recovery`

Now ,remove sd and put it in your Raspberry pi

Boot PINN

Select 'Windows 10 Desktop Core'

Just click install

After installation wait some time to make Windows 10 bootable

And it will reboot and wait some time

 Enjoy Windows 10 arm64 proffessional
