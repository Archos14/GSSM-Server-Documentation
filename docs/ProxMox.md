# Server First Boot and Installing Proxmox
First, I installed [Proxmox Virtual Environment](https://www.proxmox.com/en/proxmox-ve) by burning the ISO to a DVD.

I choose to use the latest ProxMox version available, 7.3.

Proxmox VE's documentation is available [here](https://www.proxmox.com/en/downloads/category/documentation-pve).

First thing to note: MAKE SURE both power cables are plugged in. Also, apparently a FlexibleLOM module may not be properly seated, but that could've been due to not originally having both power cables plugged in.

I burned the aforementioned ProxMox VE version 7.3 to a CD, inserted to the server, booted it up, and tried to install ProxMox normally.

Ran into an issue where no hard drives were being recognized. Trying to sort it out with iLO Networking settings
