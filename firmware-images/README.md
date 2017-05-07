# README #

ASUS RT-N600 Installation Method (base is usually sufficient):

Select the version you want (BASE or FULL)

Download the Asus recovery firmware tool from http://dlcdnet.asus.com/pub/ASUS/LiveUpdate/Release/Wireless/Rescue.zip 
This runs on windows only (It also works with a windows VM with a bridged network adapter to the ethernet port on OSX) 
-If bridging through a VM host, set the host network adapter to a manual IP of 192.168.1.100 / 255.255.255.0 with NO gateway

Plug in your ethernet to port 1 of the LAN on the router

Load up the recovery software with the selected firmware file from above, but don't press "Start Recovery"!

Plug in the router to power WHILE HOLDING the reset button in. While CONTINUING to hold the button, select "Start Recovery" Continue to hold the reset button in until it finishes and verifies!

The router will reboot and not much will happen. Wait a minute or 2.

Power off and on the router again. Voila. Set everything back to DHCP and youre good to go. L:admin P:admin

