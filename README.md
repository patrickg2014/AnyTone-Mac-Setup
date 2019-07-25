# AnyTone-Mac-Setup
(Not Official) This repository is here to help folks set up and perform functions with the AnyTone D868UV on a Mac OS.
I hope to find alternatives to Parallels in the future.
### Background info
* Radio
** Model Name:D868UV
** Firmware: 2.34
* Mac OS: Mojave (10.14)
* [Parallels: Mac & Windows Virtualization, Remote Application Server](https://www.parallels.com/) 
** Version 14.0.1
** Running Windows 10

### Setting up D868UVE Software
1. Set up a Windows 10 Parallels VM and proceed to follow the Windows install steps there.
2. Navigate to [BridgeComSystems](https://www.bridgecomsystems.com)
3. Install the latest AnyTone AT-D868UV Version 1.34 CPS software
4. At the bottom of the [BridgeComSystems Support Page](https://www.bridgecomsystems.com/pages/anytone-at-d868uv-support-page) you should find a link to download the  ****AnyTone AT-D868UV USB Drivers (zip)***
5. Unzip the downloaded zip file and right click and install the drive as an ***Administrator***
6. Connect the radio to the MAC using a USB cable and ***power it on***.
7. Parallels will prompt to ask ***where to connect this device?*** Select Windows 10
8. Right Click on the Start Menu Icon and Select ***Device Manager***
9. Validate the ***Ports*** option shows ***GD32 Virtual Com Port***. (COM3 or COM6 are both fine)
10 Launch the CPS software
11. In the top menu bar select ***Set->Com*** and validate that COM3 or COM6 is in the drop down.
12. Happy Programming!
