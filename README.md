<h1>Networking</h1>

Local area network (LAN)
-- 
A Local Area Network (LAN) is a network that connects devices within a limited area such as a home, office building, or school. A LAN allows devices to communicate and share resources in a localised environment.  

<h3>A simple LAN using Cisco Packet Tracer:</h3>

<img src="https://i.imgur.com/zXZlUdB.png" height="30%" width="40%" alt="2 PC's and a laptop connected to a switch"/>

Select 2 PCs, a laptop, and a Switch and drop them in the work environment. Connect the end devices to the switch using a Copper Straight-Through cable.

A switch is a device that operates at the data link layer of the OSI model and is used to connect devices within a LAN.

<br>

<img src="https://i.imgur.com/z8vztlc.png" height="40%" width="40%" alt="PC0's IP configuration screen"/>

To configure the devices so that they are able to communicate with each other. First set up the IP configuration of PC0. Check to use a Static IP address. Enter an IP address of 192.168.1.1 and a subnet mask of 255.255.255.0

Do the same for PC1 and Laptop0 but use an IP address of 192.168.1.2 for PC1 and an IP address of 192.168.1.3 for Laptop0
When you assign a static IP address to a device it means that the IP address has been manually configured and does not change. DHCP is a protocol that dynamically assigns an IP address to a device from a DHCP server.

An IP address is a unique numerical label assigned to each device connected to a network, allowing for communication with other devices.
A subnet mask is a 32-bit number used in conjunction with an IP address to identify the network and host portion of an address. For example, PC0 has an IP address of 192.168.1.1 and a subnet mask of 255.255.255.0, the network portion would be 192.168.1, and the host portion would be 1.

<br>

<img src="https://i.imgur.com/zUQHE2y.png" height="40%" width="40%" alt="PC0's IP configurations settings"/>

To verify that PC0 has accepted those changes enter the command ipconfig into the command prompt. This command will show the IP address and subnet mask of a device.

<br>

<img src="https://i.imgur.com/XixMYj0.png" height="40%" width="40%" alt="PC0's IP configuration screen"/>

To check if there is connectivity between 2 devices on a network use the ping command. To check for connectivity between PC0 and PC1 enter ping 192.168.1.2 in the command prompt.


